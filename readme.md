
# Simple ZX Spectrum +2 basic skin for Windows Terminal preview.

How to install:

1 - Download the background image (bgbasic2.png) to a folder in your computer (you can clone directly this repository)

2 - Open the profiles.json file with the terminal settings (use the down arrow on the terminal, click "Settings")

3 - Add this to the profiles section

    {
        "guid": "{61c54abd-c2c6-5271-96e7-009a87ff42bc}",
        "name": "WT Spectrum +2",
        "hidden": false,
        "experimental.retroTerminalEffect": false,
        "colorScheme": "speccy",
        "fontFace": "ZX Spectrum",
        "fontSize": 16,
        "padding": "20,40,20,90",
        "tabTitle": "ZX SPECTRUM +2",
        "cursorShape": "filledBox",
        "cursorColor": "#0000ff",
        "backgroundImage": "(PATH TO THE IMAGE)\\bgbasic2.png",
        "backgroundImageStretchMode": "fill",
        "startingDirectory": "%USERPROFILE%"


     }

4 - Add this to the "schemes" section

    {
        "name": "speccy",
        "background": "#c0c0c0",
        "foreground": "#000000",
        "selectionBackground": "#FFFFFF",
        "black": "#000000",
        "blue": "#0000c0",
        "brightBlue": "#0000ff",
        "brightCyan": "#00ffff",
        "brightGreen": "#00ff00",
        "brightPurple": "#ff00ff",
        "brightRed": "#ff0000",
        "brightWhite": "#ffffff",
        "brightYellow": "#ffff00",
        "cyan": "#00c0c0",
        "green": "#00c000",
        "purple": "#c000c0",
        "red": "#c00000",
        "white": "#c0c0c0",
        "brightBlack": "#000000",
        "yellow": "#c0c000"
    },


5 - Install the ZX Spectrum font from https://www.dafont.com/zx-spectrum.font

You're good to go, now you have a "ZX SPECTRUM +2" terminal mode on the terminal drop-down.

Cheers!
