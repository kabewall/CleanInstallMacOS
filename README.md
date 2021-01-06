v1.0.0
## Environment
- MacOS 10.15.7 Catalina
- Intel Mac

# 1. Install homebrew
- install homebrew on my MacOS:
[Homebrew](https://www.notion.so/Clean-Install-MacOS-4eddbca23baf41e59054970911591fb5#d5bef6a42394416fb178e3ce6aa48d1e)

# 2. Install App from brew cask
``` shell
$ brew install --cask karabiner-elements google-chrome atom texpad slack iterm2 zoomus vlc visual-studio-code
```

# 3. Install Python
```shell
# install pyenv
$ brew install pyenv
$ pyenv install -l
$ pyenv install x.x.x
$ pyenv global x.x.x

# set root
$ cd ~
$ touch .zshrc
$ echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
$ echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
$ echo 'eval "$(pyenv init -)"' >> ~/.zshrc
$ source ~/.zshrc
```

# 4. Set Atom Editor from apm

```shell
$ apm login
$ apm install hydrogen file-icons autocomplete-paths autocomplete-python highlight-selected platformio-ide-terminal
```

# 5. Install App Store Application from mas
```shell
$ brew install mas
$ mas install 497799835 539883307 1444383602
# Install LINE, XCODE, GOODNOTES5
```
