# Anycubic Kobra Dark UI
An *even more* improved UI for the Anycubic Kobra 3D Printer, forked from [jojos38](https://github.com/jojos38/anycubic-kobra-dark-ui) to make some minor changes for use on my own Kobra.

### Disclaimer
I am not responsible for any damage or malfunction caused to your printer because of those files. Any modding made to your printer is made at your own risk, this includes any damage that could happen in real life.

### Features
- Brand new UI look with a dark theme
- Starting animation shortened to remove the fading to white
- Improved buttons placements and size (bigger buttons for those who were too small and hard to tap)
- Improved translations for less ambiguity
- Much better image compression for less artifacts (The default UI was really bad)

### Known issues
- The file selection menu text becomes blue after being deselected instead of white
- The number input page input text is blue instead of white
- The language button has been disabled, this is intentional. I will only be maintaining an english version of this project, if you need any other languages then use [jojos38's version](https://github.com/jojos38/anycubic-kobra-dark-ui).

# How to install
1. Head on to the official page of the Anycubic Kobra [here](https://www.anycubic.com/products/kobra).
2. Scroll down and download the Firmware V2.7.9 OR you can build your own firmware from the Anycubic Github repository (V2.8.2).
3. Follow the instructions in the Read Me.txt of their file
4. If the installation succeed you should see `SD card Process... END !` at the top, you can then turn off the printer and remove the SD card
5. Download the latest release in the [release tab](https://github.com/ItsWiley/remastered-kobra-ui/releases).
6. Unzip the DWIN_SET folder at the root of your SD card (make sure to use a reliable SD card, the one shipped with the printer is not), do not put anything else but this folder, if you had the old folder from the official firmware, **remove it before**
7. Turn off your printer put the SD card **under the screen**, not in the printer the body. Make sure to leave it unplugged for 10 - 20 seconds to make sure the caps can discharge
8. Turn on your printer and wait until you see `SD card Process... END !` on the second line, do NOT turn off the printer before this line appears. The process shoudn't take more than 5 minutes unless your SD card is broken or very slow
9. Make sure the number next to .BIN Files shows `003` and the number next to .ICL Files `001`
10. Turn off your printer, remove the SD card
11. Turn the printer back on
