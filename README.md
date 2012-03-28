Notepad++ UDL files
==============

The windows text editor [**Notepad++**](http://notepad-plus-plus.org/) allows for extending it with so called *User Defined Languages* (UDLs) for custom or new syntax highlighting.

This repository holds such UDL files.


## Installation of UDL files

**For User Defined Languages:***

* Open Notepad++
* View -> User Defined Languages
* Import the userDefineLang XML file
* Restart Npp

*(Will be added to %APPDATA%\Notepad++\userDefineLang.xml)*


**Autocomplete:**

Copy xml file into
<InstallDIR>/plugins/API


## Specifics

Most files at the moment are re-hosts (folder *mix*), so you and me can find them more easily. Some have been changed or were newly created though, as described in the following.

### Go

The Go syntax highlighting UDL file has been severely improved.

Original version taken from the official [custom UDL wiki page](http://sourceforge.net/apps/mediawiki/notepad-plus/index.php?title=User_Defined_Language_Files). The linked file go.zip is hosted in the official sf repository.
