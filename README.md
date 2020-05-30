# Window Borders Mint19
Additional Metacity Themes from Mint 18.3 Cinnamon Edition tweaked to work in Mint 19 / Cinnamon 3.8.x

## Introduction

Just installed or upgraded to Mint 19 Cinnamon and wondering where all the Window Border theming options have gone? Missing your Ageing Gorilla, Crux, Esco etc...?

Never fear this repository contains the full set of 'missing' Window Border themes. Where necessary they have been updated to `metacity-theme-3.xml` formats to display correctly in the Cinnamon 3.8.x Themes module. Display issues have been fixed and compatibility for displaying colours from GTK3.22 themes has been improved.

The theme pack also includes several bonus themes

Mint-Y-BB & Mint-Y-Dark-BB (Big-Buttoned) variations - these have buttons 50% larger than the stock Mint-Y window borders themes.
Mint-Y-VBB & Mint-Y-Dark-VBB (Very-Big-Buttoned) variations - these have buttons 100% larger than the stock Mint-Y window borders themes.

Crux-Left - this is a Crux variant intended for users who set their titlebar button layout to left.

Cinnamox-Colours - a generic window border theme ported from the Cinnamox themes and adjusted to use the GTK theme's selected colour for the active window titlebar
Cinnamox-Colours also supports end-user resizing of the buttons and includes a small terminal based utility to switch between button-sizes. 
To use the utility for the first time after installation open a terminal ((Ctrl-Alt-T) and run `chmod +x ~/.themes/Cinnamox-Colours/scripts/cinnamox_titlebar_button_size.sh && ~/.themes/Cinnamox-Colours/scripts/cinnamox_titlebar_button_size.sh`
To run the utility again just run `~/.themes/Cinnamox-Colours/scripts/cinnamox_titlebar_button_size.sh`

## Installation

Open a terminal (Ctrl-Alt-T) and enter the following commands

* `cd /tmp`

* `wget https://github.com/smurphos/Window_Borders_Mint_19/releases/download/v.0.8/metacity_for_mint19_cinn.zip`

* `unzip -o metacity_for_mint19_cinn.zip -d ~/.themes`

Open the Themes app and the new Window Border's themes should be available for selection.

## Included Themes

![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Adwaita.png "Adwaita")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/AgingGorilla.png "AgingGorilla")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Atlanta.png "Atlanta")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Bright.png "Bright")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Crux.png "Crux")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Esco.png "Esco")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/High-Contrast.png "High-Contrast")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Metabox.png "Metabox")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Simple.png "Simple")

## Bonus Themes

![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Mint-Y-BB.png "Mint-Y-BB")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Mint-Y-VBB.png "Mint-Y-VBB")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Mint-Y-Dark-BB.png "Mint-Y-Dark-BB")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Mint-Y-Dark-VBB.png "Mint-Y-Dark-VBB")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Cinnamox-Colours.png "Cinnamox-Colours")
![alt text](https://github.com/smurphos/Window_Borders_Mint_19/blob/master/screenshots/Crux-Left.png "Crux-Left")


## Changelog

5/7/18 - v.0.1 - Initial port of version 1 and 2 themes to version 3 - release

6/7/18 - v.0.2 - Fixed version 1 and 2 themes to support Mate

12/7/18 -v.0.3 - Removed all version 1 and 2 themes. Improvements to version 3 themes to improve compatibility for displaying colours from active GTK3.22 theme.

16/7/18 - v.0.4 - Added bonus themes Mint-Y-BB and Mint=Y-Dark-BB. BB stands for Big-Buttoned...

21/10/18 - v.0.5 - Added Crux-with-icons. Added thumbnail.png to all themes in case the thumbnails aren't pre-installed.

5/11/18 - v.0.6 - Fixed HighContrast inner button prelight and pressed background color.

8/2/19 - v.0.7 - HighContrast - show buttons on regular dialogs

30/5/20 - v.0.8 - Retired Crux with Icons. Added Crux-Left for users who change the button layout to Left. Added VBB (Very Big Buttoned) variations of Mint-Y and Mint-Y-Dark. Added Cinnamox-Colours. All themes have an index.theme so can be selected in MATE.
