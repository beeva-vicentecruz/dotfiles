# dotfiles

This repository holds the configuration files and scripts I use

## How to use:

### Install ZSH

```shell
sudo apt-get install zsh
```

and make it your default shell

```shell
chsh -s $(which zsh)
```

### Install oh my ZSH

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

### Install oh my ZSH plugins (zsh-autosuggestions, zsh-syntax-highlighting)

```shell
git clone git://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
```

### Install powerline fonts

```shell
# clone
git clone https://github.com/powerline/fonts.git
# install
cd fonts
./install.sh
# clean-up a bit
cd ..
rm -rf fonts
```

### Create symbolic links to

* .vimrc
* .gitignore
* .gitconfig
* .gitmessage
* .oh-my-zsh/custom/zsh-autosuggestions.zsh
* .zshrc

You should configure your preferred powerline font in your console app and set color schema to xterm