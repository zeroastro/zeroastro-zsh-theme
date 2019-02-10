# Zeroastro ZSH Theme

Simple Oh My ZSH Theme for **Dark Backgrounds**

![Zeroastro ZSH Theme](https://github.com/zeroastro/zeroastro-zsh-theme/raw/master/zeroastro-zsh-theme.png)

## Requirements
- UNIX-like OS (Linux, macOS, BSD)
- ZSH
- [Oh My ZSH](https://github.com/robbyrussell/oh-my-zsh)
- cURL
- GIT

## Installation 

```sh
mkdir -p ~/.oh-my-zsh/custom/themes/
curl -fsSL  https://github.com/zeroastro/zeroastro-zsh-theme/raw/master/zeroastro.zsh-theme -o ~/.oh-my-zsh/custom/themes/zeroastro.zsh-theme
sed -i.bak 's/^[[:space:]]*ZSH_THEME=.*/ZSH_THEME="zeroastro"/' ~/.zshrc
exec zsh
```

