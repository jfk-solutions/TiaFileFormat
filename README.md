# TiaFileFormat
A Library to read the Siemens TIA Files

# License
At the moment there is only a comercial licence available. Please contact us (info@jfk-solutions.de) for an individual offer.

# What is supported:
 * Read the Project/PLF files or read them directly from a compressed TIA project
 * Read TIA Files from Version V10.5 - V19
 * The 3 different File Formats V10.5, V11 and V14, the other Versiones us ethe same Files but more objects
 * High level functions to extract the Program Blocks from the Projects to AutomationML format (V11-V19)
 * High level functions to extract all Images from the Projects
 * No TIA Portal needed!
 * Windows, Linux & MacOS supported

# Planned features:
 * High level function to extract Hardware Information
 * High level functions to access the Screens of WinCC Adavanced, WinCC Professional and WinCC Unified
 * High level functions to access all scripts of the WinCC Projects

Features can be improved based on an additional contract.

# Usage

## Datatypes

## Read Projects

### Open Tia Project

To open a Tia Project, you need to use a "TiaFileProvider". The FileProvider is a abstraction wich encapsulates Projects in
Archives, Streams, ...

    var tiaFileprovider = TiaFileProvider.CreateFromSingleFile(file);
    var database = TiaDatabaseFile.Load(tiaFileprovider);

### Browses through all Folders

The database root objects contain different storrage objects, the most interesting ones would be "Project" and "Library" (but the do not need to be there, all are optional)

     if (database.RootObject.StoreObjectIds.TryGetValue("Project", out var prj))
     {
         var storageBusinessObject = ((StorageBusinessObject)prj.StorageObject, "Project");
     }

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
