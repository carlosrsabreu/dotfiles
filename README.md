# My dotfiles
## Oh-my-zsh
https://github.com/ohmyzsh/ohmyzsh
```
sh -c “$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)”
```
### zsh-syntax-highlighting
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
### zsh-autosuggestions
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
## `Powerlevel10k` theme
### Installation
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
Repo: https://github.com/romkatv/powerlevel10k
Fonts: https://github.com/romkatv/powerlevel10k#fonts
iTerm 2 Solarized: https://gist.github.com/kevin-smets/8568070
## Signing Git commits
https://gist.github.com/jonathanwall/bc5c873224ad0d5c605af2cf983f1811

## Dracula Theme
```
git clone https://github.com/dracula/iterm.git
```
### Instalation
1. iTerm2 > Preferences > Profiles > Colors Tab
2. Open the Color Presets... drop-down in the bottom right corner
3. Select Import... from the list
4. Select the `Dracula.itermcolors` file
5. Select the Dracula from Color Presets...
