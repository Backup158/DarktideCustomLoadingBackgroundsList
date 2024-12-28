For use with tickbox's [Custom Loading Backgrounds mods](https://www.nexusmods.com/warhammer40kdarktide/mods/462).

Using wallpapers from Steam profile backgrounds and reuploaded art from various sources. Reuploaded wallpapers hosted on [Imgur](https://imgur.com/a/custom-loading-backgrounds-1920x1080-REhTk5C). 

Using all of these at once might kill your fps if you run a heavy setup. I don't know why, it just got worse after adding a bunch of wallpapers. I tried 200 wallpapers on a light setup (one without Extended Weapon Customization lol) and didn't notice much of a difference.

# Installation
Make sure `Load Internet` is 'On' in the Mod Options. Then do one of the following:

## Adding as a Curated List
1) Open the text file on the repository
![img1](https://github.com/user-attachments/assets/d3f54624-0bfe-41b7-8f91-0713f337d250)
2) Click on 'Raw'
![img2](https://github.com/user-attachments/assets/3a170483-db37-431e-a08c-90f855ae8b81)
3) Copy the url
![img3](https://github.com/user-attachments/assets/38711640-3019-4c8d-ba6d-1a1d07bbaac0)
4) Add the alternative list by writing `table.append(curatedLists, {"<URL DIRECTLY TO THE TEXT>"})` to `CustomLoadingBackground.lua`. The default one is on line 15, so you can use that as a reference and put other lists in the lines below. 
![img4](https://github.com/user-attachments/assets/6432934b-3647-4562-adf9-70804cdb8ea7)

## Adding as the Main List
### Method 1 (Preferred)
Copy the relevant contents of `urls.txt` and paste it into `<Darktide Mods>/CustomLoadingBackground/scripts/mods/CustomLoadingBackground/urls.txt`

### Method 2
Download `urls.txt` and put it into the `<Darktide Mods>/CustomLoadingBackground/scripts/mods/CustomLoadingBackground` folder.

Replace the existing file. Rename the existing file if you want to use it again later (whichever is named `urls.txt` is the active one. other files won't load).

# Wallpaper Choices
The file is full of Warhammer related arts. I have included some (commented out) wallpapers as an example at the beginning. Make sure each link leads directly to the image (not just to an album).

To add your own images from some other imgur album: click 'Copy Link', paste it into `urls.txt`, add '.png' to the end of the url.

**See the comment block at the top of the file for further details.**

I've included alternative lists (I guess you can call them modules? sets?) aside from the main file. These have stricter theming.


