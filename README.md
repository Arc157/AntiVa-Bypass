# AntiVa-Bypass
Offsets and hex's that bypass pg3d's antiva detection

# What is this project?
This project contains the offsets and hex's for the pg3d antiva detection i found. I decided i'd make then open source just incase someone else might try to mess with the game. The offsets and hex's are for pg3d version 21.6.1

# Offsets and hex
libunityads.so, 0x1522, FF D0 //BEQ instruction, (find in libunityads.so isReady function) 

libil2cpp.so, 0x1B39B64, 00 F0 20 E3 //Use VersionBlocker : 丈丌上且三丏丙七丁 (first usage in ida, find at line 1207) 

libil2cpp.so, 0x21FF734, 00 F0 20 E3, //Switcher.专万专丗七丁丄万丟 : MoveNext (find at line 113)

# Info
Ida is required to update to the newest version
. Must use credit if you're going to use the offsets
