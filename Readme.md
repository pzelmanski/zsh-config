# How to make a link to use .zshrc from repo:

`ln -s /mnt/c/repo/.zshrc ~/.zshrc`
while being in this repo root dir


# Git status details & pretty prompt

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

echo 'source ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc
```
