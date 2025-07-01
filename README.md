# oh-my-posh-themes
An extension of the emodipt theme which adds the python virtual environment to the prompt. Due to color clashing between the official python yellow colors and the github yellow, and between the official python blue and the path blue, I have made the path to a lavender. 

## How to use in Ubuntu/WSL
Add this to your ~/.bashrc file:
```
eval "$(oh-my-posh --init --shell bash --config 'https://raw.githubusercontent.com/johndoe133/oh-my-posh-themes/refs/heads/main/python-emodipt-extend.omp.json')"
```

If you get an error with the path, use `which oh-my-posh` to find the path of oh-my-posh and replace oh-my-posh with the path to it. For example:

```
eval "$(/home/ekj/.local/bin/oh-my-posh --init --shell bash --config 'https://raw.githubusercontent.com/johndoe133/oh-my-posh-themes/refs/heads/main/python-emodipt-extend.omp.json')"
```

## Example
![image](https://github.com/user-attachments/assets/a4dce585-a27d-4ff2-9b02-2b1718c04836)


