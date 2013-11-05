Lua to Lub Conversion:

To Compile from Lua to Lub(for 2012+ Clients):
	luac5.1.4.exe -o FileName.lub FileName.lua

To Compile from Lua to Lub(for Old Clients):
	luac5.0.2.exe -o FileName.lub FileName.lua

It will compile FileName.lua to FileName.lub

Make idnum tables from itemInfo:
1)Copy itemInfo.lub to "SeperateItemInfo" Folder, If you have .lua, just change the extension to .lub
2)If you have lua installed, just double-click "SeperateItemInfo.lua" and it will do the work.
3)If you don't have lua installed, open command prompt, go to "SeperateItemInfo" Folder, and type the following command "lua SeperateItemInfo.lua"
4)The files will be stored in "idnum" folder.
Note: This can even convert the compiled .lub file to idnum table



