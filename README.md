# Nu cho, opyat 1.12?
Magic themed minecraft modpack on 1.12 called "Nu Cho Opyat 1.12?"

## How to install
- Download minecraft laucher
- Launch and close 1.12.2 version of minecraft
- Download [forge version 14.23.5.2854](https://files.minecraftforge.net/maven/net/minecraftforge/forge/1.12.2-14.23.5.2854/forge-1.12.2-14.23.5.2854-installer.jar)
- Launch forge installer and choose `Install client`
- Inside of the launcher enter settings, and allocate at least 3 gigs of memory to the Java VM
- Depending on your launcher, modified version of minecraft won't show up in the versions list. You may need to update settings to allow that
- From the versions list choose the one that has forge-14.23.5.2854 written in it
- Launch and make sure everything is running ok
- Enter `.minecraft` folder and launch command prompt in it
- Run 
```shell
git init &&
git remote add origin https://github.com/Malien/MC-NCO1.12.git &&
git fetch &&
git checkout raw. 
```
If you dont have git installed, consider googling on how to install and use git. If your `.minecraft` already contains git repo inside of it, delete hidden `.git` folder in it
- Launch the same forge version and enjoy your time