Various collections of 1920x1080 wallpapers for use with tickbox's [Custom Loading Backgrounds mod](https://www.nexusmods.com/warhammer40kdarktide/mods/462).

Using wallpapers from Steam profile backgrounds and reuploaded art from various sources (so I can crop them). Reuploaded wallpapers hosted on [Imgur](https://imgur.com/a/custom-loading-backgrounds-1920x1080-REhTk5C).

Using all of these at once might kill your fps if you run a heavy setup. I don't know why; it just got worse after adding a bunch of wallpapers. I tried 200 wallpapers on a light setup (one without Extended Weapon Customization lol) and didn't notice much of a difference.

# Installation
Make sure `Load Internet` is 'On' in the Mod Options. Then add the list with one of the following methods:

## Adding as a Curated List (Preferred)
1) Open the text file on the repository
![File in repo](https://github.com/user-attachments/assets/d3f54624-0bfe-41b7-8f91-0713f337d250)
2) Click on 'Raw'
![Raw](https://github.com/user-attachments/assets/3a170483-db37-431e-a08c-90f855ae8b81)
3) Copy the url
![Raw url](https://github.com/user-attachments/assets/38711640-3019-4c8d-ba6d-1a1d07bbaac0)
4) Add the alternative list by writing `table.append(curatedLists, {"<URL DIRECTLY TO THE TEXT>"})` to `<Darktide Mods>/CustomLoadingBackground/scripts/mods/CustomLoadingBackground/CustomLoadingBackground.lua`. The default one is on line 15, so you can use that as a reference and put other lists in the lines below. You can comment that one out if you don't want it.
![Append](https://github.com/user-attachments/assets/6432934b-3647-4562-adf9-70804cdb8ea7)

## Adding as the Main List
Choose one of the following methods.
* Appending to the Existing Main List

  Copy the relevant contents of `urls.txt` and paste it into `<Darktide Mods>/CustomLoadingBackground/scripts/mods/CustomLoadingBackground/urls.txt`. Make sure each link leads directly to the image (not just to an album).
* Replacing the Existing Main List

  Download `urls.txt` and put it into the `<Darktide Mods>/CustomLoadingBackground/scripts/mods/CustomLoadingBackground` folder, replacing the existing file. Rename the existing file beforehand if you want to use it again later (the mod only reads `urls.txt`; other files won't be used).

# Adding Your Own Images
## Through Imgur Album
1) Click 'Copy Link'
2) Add 'i.' in front of 'imgur' and '.png' to the end of the url (or whatever file type it is)
3) Paste it into `urls.txt`

There's a tool to do the last two actions for you: https://imgur.plen.io/. Paste the link into this website first, then use the link it creates for step 3.

## From a Webpage
1) Right click on the image
2) Click `Copy Image Link`
3) Paste it into `urls.txt`

Be aware that some of these images may be thumbnails, which are low resolution! Usually, you can get the full image by clicking `Open Image in New Tab` in step 2, then copying the url from there. However, some websites don't allow access to images if visited from a direct link.

# Testing the Mod
See the list of commands on the mod description page. Using the `/bg #` chat command will display the image onscreen for you to see. With v1.2+, this preview will take up the whole screen.
![BG test command](https://github.com/user-attachments/assets/5b0819a6-934b-4cdd-a36a-57c30b2c8fea)
The list will be in random order. 

# List Contents
## _Stolen Without Remorse_ - The Main File (urls.txt)
The main file is full of Warhammer-related arts. The list is separated by which game it's from and what factions are depicted.

**See the [comment block at the top of this file](https://github.com/Backup158/DarktideCustomLoadingBackgroundsList/blob/2c93ac5eb9068bb121d18a2b46a18a1e7b586b83/urls.txt#L3C1-L10C46) for further details.**

## _The Stretched Boys_
Wallpapers that would've gone into the main file if they were truly 16:9. Most of these are just barely off, and the stretching isn't very noticable. 

## _Darktide Promo_
Promotional screenshots for Darktide

## _Steam Girl_
Art from the seasonal Steam sales in 2024, featuring Steam Girl by Nemu.

## _Winter_
Some winter stuff, mostly from Steam

## _Fraternal Love_
Art from The Coffin of Andy and Leyley
