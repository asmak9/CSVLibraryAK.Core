# C#.Net Core Import/Export CSV Library
**CSVLibraryAK.Core** provides CSV import and export feature in C#.NET Core using **Datatable** as primary data structure. You can install this library via Nuget packages. You can use this library into your any **C#.NET Core 3.1 or above framework supported** project that supports Datatable data structure. This library imports CSV file with or without header and with any number of columns into C#.NET Core Datatable structure. The import function will automatically detects the number of columns of the CSV file. Export method will export your data from C#.NET Core Datatable data structure to .csv format file.

### Nuget Installation Version 1.0.0: https://www.nuget.org/packages/CSVLibraryAK.Core/

### .NET Framework Supported Nuget Library: https://www.nuget.org/packages/CSVLibraryAK/

### Copyright (c) [Asma's Blog](https://www.asmak9.com/)

# Basic Usage

```C#

using CSVLibraryAK.Core;

// Initialization.
bool hasHeader = true;
string importFilePath = "C:\\import.csv";
string exportFilePath = "C:\\export.csv";

// Impot CSV file.
DataTable data = CSVLibraryAK.Import(importFilePath, hasHeader);

// Export CSV file.
CSVLibraryAK.Export(exportFilePath, data);

```

# Examples

1. [Console Application .NET Core](https://bit.ly/3koQyTS)
2. [ASP.NET Core MVC Application](https://bit.ly/3mmOY75)
3. [WPF .NET Core Application](https://bit.ly/37Kv3c0)

<br/>
<br/>
<br/>


Like, Share, Support, Subscribe!!!

#### YouTube: https://bit.ly/2sY1aBb 

#### Website: https://www.asmak9.com/

#### E-Store Bytezaar: https://www.bytezaar.com/

#### Facebook: https://www.facebook.com/AK.asmak9/

#### LinkedIn: https://www.linkedin.com/company/asmak9

#### Twitter: https://twitter.com/asmak/
