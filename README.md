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


