# folderizer
Just a little script that puts loose files into their own automatically named folders (minus extension).
```
/path/to/folderizer /path/to/targetdirectory
```
The above usage demonstrates how easy it is to use folderizer. All it does is to take all the loose files in the ***target*** directory and place them into their own respective folders, each named according to the file name, minus the extension.

Originally, I built the script to take a -maxdepth argument, similar to the find command, but scrapped it since it had the side-effect of placing already-folderized files into ever-deeper levels. It just wasn't worth the effort of making that version smarter, so, for now, the script will only act on the specified target directory and will not recurse.