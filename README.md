# vim config

Deploy with `setup_vim` in `penguin-dev-tools`

#### Additional Steps

`YouCompleteMe` plugin requires extra setup:
```sh
cd $HOME/.vim/bundle/YouCompleteMe
git submodule --init --recursive
python3 install.py
```
