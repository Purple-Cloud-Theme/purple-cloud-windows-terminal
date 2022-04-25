# Purple Cloud for Windows Terminal
The port of the [Purple Cloud Theme](https://github.com/Purple-Cloud-Theme/purple-cloud-theme) for [Windows Terminal](https://github.com/microsoft/terminal).


## Install
In the `settings.json` settings file for Windows Terminal, find the `schemes` section and add the colors of the desired variant to the list:

- Color Scheme:
```json
{
    "name": "Purple Cloud Default",
    
    "background": "#090b10",
    "foreground": "#15fd00",
    
    "cursorColor": "#FFFFFF",
    "selectionBackground": "#FFFFFF",

    "black": "#000000",
    "blue": "#000080",
    "brightBlack": "#2f3b54",
    "brightBlue": "#0000FF",
    "brightCyan": "#00cef7",
    "brightGreen": "#00FF00",
    "brightPurple": "#eb5cff",
    "brightRed": "#be1100",
    "brightWhite": "#FFFFFF",
    "brightYellow": "#b5c01c",
    "cyan": "#008080",
    "green": "#93ff00",
    "purple": "#b700f9",
    "red": "#E60026",
    "white": "#C0C0C0",
    "yellow": "#FFFF00"
}
```

- Result: `settings.json`
```json
    "schemes" :
    [
        {
            "name": "Purple Cloud Default",
            
            "background": "#090b10",
            "foreground": "#15fd00",
            
            "cursorColor": "#FFFFFF",
            "selectionBackground": "#FFFFFF",

            "black": "#000000",
            "blue": "#000080",
            "brightBlack": "#2f3b54",
            "brightBlue": "#0000FF",
            "brightCyan": "#00cef7",
            "brightGreen": "#00FF00",
            "brightPurple": "#eb5cff",
            "brightRed": "#be1100",
            "brightWhite": "#FFFFFF",
            "brightYellow": "#b5c01c",
            "cyan": "#008080",
            "green": "#93ff00",
            "purple": "#b700f9",
            "red": "#E60026",
            "white": "#C0C0C0",
            "yellow": "#FFFF00"
        },
        {
            ...
        }
    ]
```

---

<p align="center">
    <a href="https://opensource.org/licenses/MIT">
        <img src="https://img.shields.io/badge/License-MIT-eb5cff.svg?style=flat-square"/>
    </a>
</p>