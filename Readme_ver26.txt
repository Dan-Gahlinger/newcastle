
The New Castle V26 - Released Feb 22/2024

The LINUX, MAC (Intel x86_64), and Raspberry Pi 3B versions of the New Castle v26 is also included, it is the same code as the DOS/Windows version, should not have any bugs!
But, please report errors.  The debugging mode has been left intact in order to facility this...

HINT command has been re-added, but it's all covered in the docs, user guide, intro and instructions, so not necessary.

SAVE and RESTORE functions have been added - single slot SAVE availale
RESTORE is ONLY available at the start of a new game - it will prompt you
SAVE is limited and restricted in certain places, events, etc, and has a minimum move count. eg: The game will not save if you are in the maze

simply unzip to any place you like, it will create its own directory. and read the castle_user_guide files (DOC or PDF) for information
for the linux version - decompressing the file downloaded with create a directory like ~/newcastle, then simply cd ~/newcastle
then run the Linux version of the game supplied: newcast_linux (eg: ./newcast_linux) to run it

The Linux, Mac, and Raspberry Pi versions need read/write access to its own files as save games and such create new files or update as you'd expect they'd need to...

The MAC (Intel) Version has been ressurected! Finally I've been able to build the Mac binary. Unpacking and playing the Mac version is identical to the Linux version above
Except the Mac binary is called: newcastle_mac
it'll decompress creating a newcastle directory and putting eveyrthing you need in there, then just change to that dir
and type: ./newcastle_mac

The Rasperry Pi 3B Version has finally been completed! Unpacking and playing the Raspberry Pi version is identical to the Linux or Mac versions above
Execpt the Rpi binary is called: newcastle_rpi
it'll decompress creating a newcastle directory and putting everything you need in there, then just change to that dir
and type: ./newcastle_rpi

If you are using the old v22pre version - then unzip the v26_update over-top, over-writing needed files - it's preferred to uninstall/remove old version and install new from scratch

Note: The Raspberry Pi 3B (Arm) version of Castle is also now completed, and has been made available
