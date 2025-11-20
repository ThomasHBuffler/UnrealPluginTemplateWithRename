# UnrealPluginTemplateWithRename
An unreal engine plugin with the different modules, editor, runtime and uncooked, with a simple renamer.

https://github.com/MagForceSeven/Starfire/ was used for the folder structure (Nothing else)
The renamer is simple, it searches the .h .cpp .build.cs and .uplugin files and replaces. 
If the search term it finds is all lower or upper case (Like the API export macros in classes) then it will use the case.

So it'd work well on the blank pluign, but don't try to use the replacer without understandign / modifying it to catch other cases.

If you want it to work on other text editable files as well, just edit the powershell script and add it to the list at the top.

