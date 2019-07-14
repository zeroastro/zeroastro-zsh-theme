# Zeroastro ZSH Theme

Simple Oh My ZSH Theme for **Dark Backgrounds**

![Zeroastro ZSH Theme](https://github.com/zeroastro/zeroastro-zsh-theme/raw/master/zeroastro-zsh-theme.png)

## Requirements
- ZSH
- [Oh My ZSH](https://github.com/robbyrussell/oh-my-zsh)
- CURL

## Installation

```sh
mkdir -p $HOME/.oh-my-zsh/custom/themes/ && \
    curl -fsSL  https://github.com/zeroastro/zeroastro-zsh-theme/raw/master/zeroastro.zsh-theme -o $HOME/.oh-my-zsh/custom/themes/zeroastro.zsh-theme && \
    sed -i.bak 's/^[[:space:]]*ZSH_THEME=.*/ZSH_THEME="zeroastro"/' $HOME/.zshrc && \
    exec zsh
```
