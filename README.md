# Balatro Port for the PS VITA

===
#### YOU HAVE TO LEGALLY OWN A COPY OF BALATRO ON STEAM TO PLAY THIS PORT.
#### OVERLCLOCKING IS VERY STRONGLY RECOMMENDED.
#### WE HAVEN'T TRIED ANY CRAZY RUNS AND DON'T KNOW HOW THE VITA HANLDLES IT
===

Credits to isage ([Github](https://github.com/isage), [Reddit](https://reddit.com/user/isage_dna)) for the original LÖVE engine port to the Vita used in his [Mari0 port](https://github.com/isage/Mari0-vita) :) 

Credits to Jafeth ([Github](https://github.com/Jafeth12), [Reddit](https://www.reddit.com/user/Skrubaso/)) for helping a lot with actually porting the game.

## Known issues, currently being worked on:
- Flame shader not working.
- Game runs at around 20fps.
- Shaders take a long time to compile.
- Touchscreen does not work.

## Instructions to apply port

- Download both the VPK and the ZIP file included in the latest Release.
- Extract the zip file wherever you want.
- Copy Balatro.exe (YOUR_STEAM_INSTALLATION_PATH/steamapps/common/Balatro/Balatro.exe) to the folder where the extracted zip resides.

**Retrieve .exe file on MacOS**

- Download [Crossover from CodeWeavers](https://www.codeweavers.com/crossover/download)
- Install the Steam client from Crossover
- Once installed, log in to your Steam account and download Balatro, this will be the Window version
- In the Crossover under "BOTTLES" → "BOTTLES ACTIONS" click "Open C: Drive
- Navigate to */Program Files (x86)/Steam/steamapps/common/Balatro*
- Copy Balatro.exe

#### IF YOU'RE ON WINDOWS:

- Execute windows_patch.bat to apply the patch.

#### IF YOU'RE ON UNIX (LINUX/MAC):

- Install xdelta3 using your packet manager of choice (PATCH WILL NOT APPLY PROPERLY IF ANY OTHER VERSION OF IS USED, HAS TO BE xdelta3).
    - Mac (using brew): ```brew install xdelta``` (we dont have mac, we cant try this out. if any mac user can confirm this does actually install xdelta3 and works it would be appreciated)
    - Debian/Ubuntu: ```sudo apt install xdelta3```
    - Arch: ```sudo pacman -S xdelta3```
    - Fedora: ```sudo dnf install xdelta```
- Execute unix_patch.sh to apply the patch.


#### AFTER PATCHING:

- In your Vita, open VitaShell to connect the console with your PC and copy both the VPK and the patched _game.love_ file.
- Install the VPK on your Vita.
- Copy the _game.love_ file to ux0:/app/BALA00001/
- Enjoy!
> To use other languages follow [this](https://www.reddit.com/r/VitaPiracy/s/PnIFvNg45C) reddit comment.
                     
**If you want to support me you can leave a tip on my patreon: https://patreon.com/daexxx/**

[![Star History Chart](https://api.star-history.com/svg?repos=Daexxxx/Balatro-Vita&type=Date)](https://www.star-history.com/#Daexxxx/Balatro-Vita&Date)
