[![Board Status](https://chuongpqvn1107.visualstudio.com/3fc5c74f-7402-469c-ad3c-a1229022977a/aa28fd71-1156-44d8-9501-c70eafbb2422/_apis/work/boardbadge/468dfdc4-bdb6-406f-896c-86d4812e7c31)](https://chuongpqvn1107.visualstudio.com/3fc5c74f-7402-469c-ad3c-a1229022977a/_boards/board/t/aa28fd71-1156-44d8-9501-c70eafbb2422/Microsoft.RequirementCategory)

# AutoCADLookup

![Autocad API](https://img.shields.io/badge/Revit%20API-2021-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgray.svg)
![.NET](https://img.shields.io/badge/.NET-4.7.2-blue.svg)
[![License](http://img.shields.io/:license-mit-blue.svg)](http://opensource.org/licenses/MIT)

Interactive Autocad BIM database exploration tool to view and navigate element properties and relationships.

### Setup

Open the SnoopAutoCADCSharp.sln on Visual Studio 2017. All references should be ready for AutoCAD 2022 default install path, otherwise go to project properties >> References, then click on Reference Paths and adjust. Build the project in Release, the DLL should be placed at same folder. Copy the entire .bundle folder to C:\Program Files\Autodesk\Autodesk\ApplicationPlugins folder and launch Autocad.

### Version

The most up-to-date version provided <a href="[link](https://github.com/chuongmep/SnoopAutoCADCSharp/releases/)">here</a>  is for Autocad 2022.
- <a href="https://github.com/chuongmep/AutoCADLookup/releases/tag/1.0.0">2022</a>  for Autocad 2022
- <a href="https://github.com/chuongmep/AutoCADLookup/releases/tag/1.0.0">2021</a>  for Autocad 2021
- <a href="https://github.com/chuongmep/AutoCADLookup/releases/tag/1.0.0">2020</a>  for Autocad 2020
- <a href="https://github.com/chuongmep/AutoCADLookup/releases/tag/1.0.0">2019</a>  for Autocad 2019
- <a href="https://github.com/chuongmep/AutoCADLookup/releases/tag/1.0.0">2018</a>  for Autocad 2018

# Usage

- On AutoCAD , command the "SnoopAutocad" option, the main form should appear. At the left side is a list of the main collections on the active document. On the right side, the properties of the item selected on the left.

- Can continue Snoop Database to check.

![](Documents/_Image_bfad9808-fa10-4857-8d77-f1f0b161433f.png)

### Author 

First Project write sypport Civi3D with language VB.NET by <a href="https://github.com/augustogoncalves">Augusto Goncalves</a> <a href="https://twitter.com/augustomaia">@augustomaia</a> , member of the Autodesk Developer Technical Services team.

Now project update in .NET C# by <a href="https://github.com/htlcnn">htlcnn</a> and <a href="https://github.com/chuongmep">Hồ Văn Chương</a> 

### Known Issues

The tool may stop working on some properties that cannot be reflected (using .NET).

### Demo

![](Documents/SnoopCad.gif)

### Release History

1.0.0 : First Release


