# setup
Links and preferences for quick setup of personal development environment

## Heavily borrowed from following pages
- Mac - http://sourabhbajaj.com/mac-setup/Homebrew/README.html
- Windows - https://scotch.io/tutorials/get-a-functional-and-sleek-console-in-windows
- https://github.com/mdo/config

## Setup macOS (Big Sur and newer)
- Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)")"
```
- Oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
- Copy [`.zshrc`](.zshrc) contents
- Install [Ocean theme](https://github.com/mdo/ocean-terminal) for terminal


## Setup Windows
<details>
  <summary>Click to expand!</summary>
- Install [Git](https://git-scm.com/download/win)
- Install [ConEmu](https://conemu.github.io/)
- Choose `{Bash::Git bash}` as startup task on inital launch config
- Open Settings and Import [`ConEmu.xml`](ConEmu.xml)
- Copy [`.bash_profile`](.bash_profile) to User home directory (`%HOMEPATH`)
- If needed, add a line in bash profile to fast navigate to default dev directory `cd f:/dev`
- Reload bash profile `source ~/.bash_profile`
</details>


## Dev dependencies
- [nvm](https://github.com/creationix/nvm) (Mac)
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
```
- [nvm-windows](https://github.com/coreybutler/nvm-windows) (Windows Installer)
- Grunt `npm install -g grunt-cli`


## Sublime Text
- Install Sublime Text 4 [[Link](http://www.sublimetext.com)]
- Install Package Control (`Cmd+Shift+P` > `Install Package Control`)
- Install packages through Package Control
  - [Ayu](https://github.com/dempfi/ayu)
  - [LESS](https://github.com/danro/LESS-sublime/)
  - [Emmet](https://github.com/sergeche/emmet-sublime/)
  - [GitGutter](https://github.com/jisaacks/GitGutter)
  - [SidebarEnhancements](https://github.com/titoBouzout/SideBarEnhancements)
  - [Color Highlight](https://github.com/Kronuz/ColorHighlight)
  - [Color Convert](https://github.com/zhouyuexie/ColorConvert)
- Copy personal preferences file ([Preferences.sublime-settings](/Preferences.sublime-settings))

## SSH key generation
- Remove existing remote and add SSH address instead (if needed)
  `git remote rm origin` `git remote add origin git@github.com:{repoowner}/{reponame}.git` 
- Generate new key (default path, no passphrase)
  `ssh-keygen -t rsa`
- View key contents
  `cat ~/.ssh/id_rsa.pub`
- Copy and add as new key in GitHub (https://github.com/settings/keys)
