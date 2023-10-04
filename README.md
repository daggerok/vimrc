# vimrc
My ~/.vimrc config

just in case backup current local .vimrc config

```bash
cp -Rfv $HOME/.vimrc $HOME/.zshrc-$(date +%Y-%m-%d)-backup
```

install new .vimrc file

```bash
curl -sS https://raw.githubusercontent.com/daggerok/vimrc/main/.vimrc >> $HOME/.vimrc
```

or manually add necessary configuration

```bash
echo '
filetype plugin indent on
"set term=builtin_ansi
set term=xterm-265color
syntax on
' > ~/.vimrc
```
