By FelixTheCat1970

v1 -initial
v2 -disable antialias by default because not necessary and cause graphic bugs
   -port codes and config info for PS2 to PS4 build

### Hokuto no Ken - Shinpan no Sousousei - Kengou Retsuden 北斗の拳 審判の双蒼星 拳豪列伝 (Japan) SLPM_666.60
Chages:
- +Autoboot - Enable Native Progressive Scan video mode (call-function)
- +No interleacing (of course sdtv mode call disable it)
- +640x480 pixels-lines enabled (instead default 640x448) more viewable area, also for Integer scaling
- disable antialias by default because not necessary and cause graphic bugs

!!! This only work in progressive signal TV|Monitors setups !!!
Ps2: with component cables - progresive signal setups
Ps3 backward ps2 hardware compactible: component - hdmi cables, with 480p-720p-1080p modes

download readme for instructions or visit this link more info https://felixthecat1970.github.io/gamepatches-blog/blog/ps2/post-ps2-sb-hk/

How to patch:
1. use PS2 Patch Engine tool by pelvicthrustman 1.03 from here:
https://www.psx-place.com/resources/ps2-patch-engine-by-pelvicthrustman.694/

2. Copy "patch" lines to tool according your game version, select:
-Browse your game dump
-patch > format> "PNACH"
-copy "patch" lines according your game version
-patch and test.

-Hokuto no Ken Shinpan no Sousousei Kengou Retsuden (Japan) SLPM_666.60

patch=0,EE,20292720,extended,A38286E8
patch=0,EE,202ACA50,extended,24020000
patch=0,EE,202B3E04,extended,A040D586

!!!disable antialias option in game menu for 640x480!!!

Database match: redump.org
Hokuto no Ken: Shinpan no Sousousei: Kengou Retsuden
北斗の拳　審判の双蒼星　拳豪列伝 - SLPM 66660 / SLPM 66941
SHA1: a0392092a456a9c1a6373ae174138c48dcb471ca

PS2 to PS4
visit link for code instructions:
https://felixthecat1970.github.io/gamepatches-blog/blog/ps4/post-ps4-ps2_test1/