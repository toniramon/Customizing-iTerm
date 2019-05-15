# Reminder: How to custom iTerm for MacOS.

## Prerequisites

- iTerm2

`brew cask install iterm2`

- oh my zsh

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

Download Font: Meslo LG S for Powerline

`https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20S%20Regular%20for%20Powerline.ttf?raw=true`


## Installation

Install the font archive on your iTerm2

iTerm2 > Preferences > Profiles > Change Font > Meslo LG S for Powerline

Now let’s configure your ZSH theme settings:

`cd ~
nano .zshrc`

`ZSH_THEME="agnoster"`


9. Save you changes (CTRL-X if you’re using Nano, continue editing forever if you’re using Vi or Vim).

10. Quit and restart Terminal.

11. You should now see your new theme in place.


** now install it on vsCode.
