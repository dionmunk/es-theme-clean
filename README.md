# Clean

[![Creative Commons](https://flat.badgen.net/badge/license/CC-BY-NC-4.0/orange)](https://creativecommons.org/licenses/by-nc/4.0/)

Clean is a simple, modern theme for Emulation Station and RetroPie with a minimal focus that is designed to work on a variety of screen sizes.

The theme supports resolutions from 320x240 and up. There are custom templates for different screen resolutions and you will want to customize the template based on the screen you plan to use. Many of the system logos are from the Carbon theme by Eric Hettervick with small tweaks to make them look nice on a black background.

## Screenshots

### Flat Panel TV (16:9 Aspect Ratio)

![16:9 Main View](https://i.imgur.com/aly1VRZ.png "16x9 Main View")

![16:9 Basic View](https://i.imgur.com/DFLUsmV.png "16x9 Basic View")

![16:9 Detailed/Video View](https://i.imgur.com/ekGue2V.png "16x9 Detailed/Video View")

![16:9 Bezel View](https://i.imgur.com/l6HJVyr.png "16x9 Bezel View")

### RetroFlag GPi Case Screen (4:3 Aspect Ratio at 320x240 resolution)

![320x240 Main View](https://i.imgur.com/1Ir6hqp.png "320x240 Main View")

![320x240 Basic View](https://i.imgur.com/xyDZgDt.png "320x240 Basic View")

![320x240 Detailed/Video View](https://i.imgur.com/L5LtWsN.png "320x240 Detailed/Video View")

## Features

- support for system, basic, detailed and video views
- displays all available metadata
- support for custom collections
- matching static and animated splashscreens
- matching loading animation
- 320x240 layout for use on small screens like Retroflag GPi Case
- 4:3 layout for use on CRT monitors
- 16:9 layout for use on flat panel TVs
- 16x10 layout for use on flat panel monitors
- Alternate 4:3, 16:9, and 16:10 layouts that place a CRT-like bezel over the game screenshot and/or video. Only works correctly if Use OMX Player is set to Off in the EmulationStation settings menu. See theme.xml file for more details.

## Customize

To customize Clean to fit properly to your screen, customize the `theme.xml` file and change the template to the template that matches your screen aspect ratio.

Clean's default aspect ratio template is 16:9, which should work for most flat panel LCD TVs. The 4:3 template is for CRT screens, and the 16:10 template is for many computer monitors and some flat panel LCD TVs. The 320x240 template was made for very small screens like the RetroFlag GPi Case.

## Installing

Clean has officially been [added](https://github.com/RetroPie/RetroPie-Setup/pull/3038) to RetroPie and can be installed within the RetroPie Setup if you have the latest RetroPie Setup Script.

- Go to **ES THEMES** in the Configuration menu.
- Scroll down and select entry `192 Install dionmunk/clean`
- After the theme is installed, go back to Emulation Station
- Press **Start** on your input device to get to the **MAIN MENU**
- Select **UI SETTINGS**
- Scroll down to **THEME SET** and using left/right select **CLEAN**
- Press **B** twice to back out of the menu and your theme will change to **CLEAN**

**NOTE:** If Clean isn't in the list of themes that are available to install, you need to update your RetroPie Setup Script.

- Go to **RETROPIE SETUP** in the Configuration menu.
- Scroll down and select entry **Update RetroPie-Setup script**
- You'll be asked if you want to update the script, select **Yes**
- Select **OK** when it says it fetched the latest version.
- Select **OK** again when it notifies you about the RetroPie disclaimer.
- Then **Exit** at the bottom
- Then follow the directions above

### Manual Installation

- make sure your RetroPie is connected to the internet
- on your RetroPie quit out of Emulation Station so that you are in the terminal
- create a folder `~/.emulationstation/themes` if it does not exist
- run these commands in the terminal
  
  ``` bash
  cd ~/.emulationstation/themes
  git clone git@github.com:dionmunk/es-theme-clean.git
  ```

- after the theme is downloaded, go back into Emulation Station and select Clean from the setup menu

### Alternate Install

- download the zip archive of the Git repo: [Download](https://github.com/dionmunk/es-theme-clean/archive/master.zip)
- extract the zip archive into a folder named `es-theme-clean`
- follow the instructions to [transfer ROMS to your RetroPie](https://github.com/retropie/retropie-setup/wiki/Transferring-Roms), but copy the `es-theme-clean` folder to the `~/.emulationstation/themes` folder on your RetroPie
- if the `~/.emulationstation/themes` folder doesn't exist on your RetroPie, then create it and copy `es-theme-clean` to it
- after you've copied the theme to the RetroPie, go into Emulation Station and select Clean from the setup menu

## Future Plans

- grid view support

## Acknowledgements

- many logo graphics are from the default [Carbon theme](https://github.com/RetroPie/es-theme-carbon/) made by Eric Hettervik.

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).
