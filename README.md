# setup
Links and preferences for quick setup of personal development environment

## Heavily borrowed from following pages
- http://sourabhbajaj.com/mac-setup/Homebrew/README.html
- https://github.com/mdo/config

## Setup Mac OS X Terminal
1. Install XCode from App Store
2. Install XCode command line tools `xcode-select --install`
3. Homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
4. Load [`.bash_profile`](.bash_profile)
5. zsh  `brew install zsh zsh-completions`
6. Oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
7. Set Oh-my-zsh as default shell `chsh -s /bin/zsh`
8. Install [Ocean theme](https://github.com/mdo/ocean-terminal) for terminal


## Dev dependencies
1. [NodeJS](https://nodejs.org/en/download/)
2. Grunt `npm install -g grunt-cli`


## Sublime Text
1. Install Sublime Text 3 [[Link](http://www.sublimetext.com/3)]
2. Install Package Control [[Link](https://packagecontrol.io/installation)]
3. Install packages through Package Control
  - [Predawn](https://github.com/jamiewilson/predawn)
  - [Tomorrow Color Schemes](https://github.com/theymaybecoders/sublime-tomorrow-theme/)
  - [CSS3](https://github.com/y0ssar1an/CSS3)
  - [LESS](https://github.com/danro/LESS-sublime/)
  - [Emmet](https://github.com/sergeche/emmet-sublime/)
  - [GitGutter](https://github.com/jisaacks/GitGutter)
  - [SidebarEnhancements](https://github.com/titoBouzout/SideBarEnhancements)
4. Remove Package "CSS"
5. Copy personal preferences file ([Preferences.sublime-settings](/Preferences.sublime-settings))
