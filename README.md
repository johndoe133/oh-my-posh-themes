# Intro
This is just a repo for myself to save the themes that I make and remember how I use oh-my-posh in WSL and windows terminal and vscode. 

# Looks
It will look like this:

![image](https://github.com/user-attachments/assets/5f6ae0a9-0bc7-4b39-b417-0f3e9de16187)


# Themes

## python-emodipt-extend
An extension of the emodipt theme which adds the the following things to the prompt:
- Python virtual environment in official python blue
- Changed path to a lavender due to color clash with python virtual environment
- Changed path style from full (displays entire path) to `agnoster` which displays the first directory (usually ~ for home) and then the final directory
  - Changed the intermediate file icons for the path from .. to an open folder nerd icon
- Added an icon for the OS at the start of the path
- Changed the Icon for which bash script type you are using (bash, pwsh, etc.) to have an icon that changes depending on which type you are using, not just the text itself. 

# How to use oh-my-posh
## Ubuntu/WSL
Add this to your ~/.bashrc file:
```
eval "$(oh-my-posh --init --shell bash --config 'https://raw.githubusercontent.com/johndoe133/oh-my-posh-themes/refs/heads/main/themes/python-emodipt-extend.omp.json')"
```

If you get an error with the path, use `which oh-my-posh` to find the path of oh-my-posh and replace oh-my-posh with the path to it. For example:

```
eval "$(/home/ekj/.local/bin/oh-my-posh --init --shell bash --config 'https://raw.githubusercontent.com/johndoe133/oh-my-posh-themes/refs/heads/main/themes/python-emodipt-extend.omp.json')"
```

## Powershell
use the command 

```
notepad $PROFILE
```

Copy paste this into the file:
```
oh-my-posh init pwsh --config "C:\Users\ekjensen\AppData\Local\Programs\oh-my-posh\themes\00-eric-emodipt-extend.omp.json" | Invoke-Expression
```

# Installing and using a nerd font
This will cover using JetBrains Mono nerd font. 

## Installing a nerd font
In windows, simply find the nerd font you want (must have mono) in [here](https://www.nerdfonts.com/font-downloads). Unzip and highlight all the `.ttf` files, and right click and install them. 

### Using a nerd font in VSCode
To change the font in vscode to a nerd font, use this:

Change the terminal font and editor font to this: 

```
Consolas, 'Courier New', monospace,  'JetBrainsMono Nerd Font Mono'
```

### Using a nerd font in windows terminal
Change the font face by going to settings, click on defaults, and change the font face to "JetBrainsMono Nerd Font Mono"


