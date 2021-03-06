UI Customization Sample
=======================

Demonstrates
------------
This sample demonstrates how to customize the Windows Error Reporting UI when creating and submitting
a generic report.

Languages
---------
This sample is implemented in the C programming language.

Files
-----
     UICustomizationSample.c            Source code for the sample
     UICustomizationSample.vcproj       Visual C++ 2008 project file
     UICustomizationSample.sln          Visual Studio 2008 solution file
 
Prerequisites
-------------
Windows SDK v6.0 or newer.
Windows Vista or Windows Server 2008 operating system, or newer.

Building the Sample
-------------------
To build the sample using the command prompt:
     1. Open the Windows SDK command line shell and navigate to the directory.
     2. Type: msbuild UICustomizationSample.sln

To build the sample using Visual Studio 2008 or Visual C++ 2008 Express:
     1. Open Windows Explorer and navigate to the UICustomizationSample directory.
     2. Double-click the icon for the UICustomizationSample.sln file to open the file in Visual Studio.
     3. Add the path to the Windows SDK Include folder to the "Additional Include Directories" setting of the project.
     4. Add the path to the Windows SDK Lib folder to the "Additional Library Directories" setting of the project.
     5. In the Build menu, select Build Solution. The application will be built in the default \Debug or \Release directory.

Running the Sample
------------------
1. Open a command prompt and navigate to the Release or Debug directory under UICustomizationSample.
2. Run UICustomizationSample.exe (no command-line arguments).


THIS CODE AND INFORMATION IS PROVIDED "AS IS" WITHOUT WARRANTY OF
ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING BUT NOT LIMITED TO
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND/OR FITNESS FOR A
PARTICULAR PURPOSE.

Copyright (c) Microsoft Corporation. All rights reserved.
