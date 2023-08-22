## Homebrew
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```shell
brew install git
```

```shell
git clone https://github.com/mmicire/home.git
```

```shell
brew bundle --file brewfile.work
```

## Oh My Zsh
```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Set app directory

```shell
echo "export HOMEBREW_CASK_OPTS="--appdir=~/Applications --fontdir=/Library/Fonts"" > ~/.zshrc
```

## zsh 
```
git clone https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k
```
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
```
git clone https://github.com/nobeans/zsh-sdkman.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/sdkman
```

## custom env
```shell
mv ~/home/.z* ~
```

## enable touch ID for sudo
Add this to top of file
```
code auth sufficient pam_tid.so
```
