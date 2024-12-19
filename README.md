# Albert .config repository

## Clonning repo

Clone repo into `~/.config`
```
git clone https://github.com:riscuus/.config.git "${XDG_CONFIG_HOME:-$HOME/}"/.config
```

## Creating symbolic links for bashrc and inputrc

```
cd ~
ln -s .config/terminal/.bashrc .bashrc
ln -s .config/terminal/.inputrc .inputrc
```

## Installing dependencies that are needed for nvim

```
sudo apt update
sudo apt install make
sudo apt install gcc
sudo apt install g++
sudo apt install nodejs
sudo apt install unzip
sudo apt install xclip
sudo apt install ripgrep
```
