# Macbook setup

## Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Install Git

```bash
brew install git
```

## Install Node.js

```bash
brew install node
```

## Install zsh

```bash
brew install zsh
```

## Install Oh My Zsh

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install Powerlevel10k

```bash
brew install romkatv/powerlevel10k/powerlevel10k
```

### Set Zsh theme to Powerlevel10k

```bash
echo 'source /usr/local/opt/powerlevel10k/powerlevel10k.zsh-theme' >>! ~/.zshrc
```
