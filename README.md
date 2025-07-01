# Intro
This is just a repo for myself to save the themes that I make and remember how I use oh-my-posh in WSL and windows terminal and vscode. 
An extension of the emodipt theme which adds the python virtual environment to the prompt. Due to color clashing between the official python yellow colors and the github yellow, and between the official python blue and the path blue, I have made the path to a lavender. 

## How to use in Ubuntu/WSL
Add this to your ~/.bashrc file:
```
eval "$(oh-my-posh --init --shell bash --config 'https://raw.githubusercontent.com/johndoe133/oh-my-posh-themes/refs/heads/main/themes/python-emodipt-extend.omp.json')"
```

If you get an error with the path, use `which oh-my-posh` to find the path of oh-my-posh and replace oh-my-posh with the path to it. For example:

```
eval "$(/home/ekj/.local/bin/oh-my-posh --init --shell bash --config 'https://raw.githubusercontent.com/johndoe133/oh-my-posh-themes/refs/heads/main/themes/python-emodipt-extend.omp.json')"
```

## Installing and using a nerd font
This will cover using JetBrains Mono nerd font. 

## Installing a nerd font
In windows, simply find the nerd font you want (must have mono) in [here](https://www.nerdfonts.com/font-downloads). Unzip and highlight all the `.ttf` files, and right click and install them. 

### In VSCode
To change the font in vscode to a nerd font, use this:

Change the terminal font and editor font to this: 

```
Consolas, 'Courier New', monospace,  'JetBrainsMono Nerd Font Mono'
```

### In windows terminal
Change the font face by going to settings, click on defaults, and change the font face to "JetBrainsMono Nerd Font Mono"

## Example
![image](https://github.com/user-attachments/assets/a4dce585-a27d-4ff2-9b02-2b1718c04836)


