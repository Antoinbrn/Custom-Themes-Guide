# Making Custom Themes in ARK-4.

## Requirements:
* **Python3**
* [**Script For THEME.ARK**](pkg%20Script/pkg.py).<br/>

**Note: If you are using Windows make sure you have show file extentions enabled**

## Step 1:

### Folders:
* Create a folder with any name you want to give it.
* Inside the folder, create a subfolder named **resources**. **This will be the folder with everything inside.**

### Wallpaper and Loading Screen:
* Find a wallpaper image you like and name it: **DEFBG.PNG**.
  * The Wallpaper needs to be a **480x272** resolution.
* Find a loadign screen image you like and name it: **LOADING.PNG**

### Menu Icons (100x100 or 80x80):
* File Explorer named: **BOX.PNG**
* Internet Browser named: **BROWSER.PNG**
* Exit named: **EXIT.PNG**
* FTP Connection named: **FTP.PNG**
* Game menu named: **GAME.PNG**
* Plugins named: **PLUGINS.PNG**
* Settings named: **SETTINGS.PNG**

### Music:
* Music in main menu named: **SOUND.MP3**
* Music playing when booting a game named: **BOOT.MP3**

## Step 2:
* Place the code next to the ressources folder
* Open the terminal inside the root folder
* Run the script with ```python3 pkg.py``` and a file named THEME.ARK should pop up

## Step 3:
* Go to the directory ```PSP/SAVEDATA/ARK_01234/```
* Copy the new THEME.ARK inside or create a folder if there's more themes
* Disconnect the psp or eject the sd card

## Step 4:
* Launch the custom launcher
* Navigate to folders
* Navigate to ```PSP/SAVEDATA/ARK_01234/THEME.ARK``` or ```PSP/SAVEDATA/ARK_01234/Folder with THEME.ARK```

And That's it.

## Disclamer
The python script comes from this [Repo](https://github.com/PSP-Archive/ARK-4/blob/main/extras/menus/arkMenu/pkg.py).