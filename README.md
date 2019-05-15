# Reminder: How to custom iTerm for MacOS.

## Prerequisites

- iTerm2

`brew cask install iterm2`

- Oh My ZSH

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

Download Font: Meslo LG S for Powerline

https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20S%20Regular%20for%20Powerline.ttf?raw=true


## Installation

Install the font archive on your iTerm2

iTerm2 > Preferences > Profiles > Change Font > Meslo LG S for Powerline

Now let’s configure your ZSH theme settings:

~~~ 
cd ~
nano .zshrc 
~~~

`ZSH_THEME="agnoster"`


Save you changes (CTRL-X if you’re using Nano).

Quit and restart iTerm.


Voilà, magic happen.




## vsCode with custom terminal.

Once we have dont all the previous steps we can start customizing vsCode:

- Change font:
vsCode > Preferences > Configurations > User Config
On the top bar find: Editor: Font Family
1 - Editor: Font Family -> Meslo LG S for Powerline
2 - Terminal > Integrated: Font Family -> Meslo LG S for Powerline
3 - Terminal > External: Osx Exec: iterm.app
