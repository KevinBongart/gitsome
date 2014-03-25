![screenshot](http://cl.ly/UdeK/screenshot.png)

gitsome is a nice and simple oh-my-zsh prompt with some git:

1. The current directory
2. The current git branch name (if any)
3. The git status on the current branch (red/green)

This fork of Matt's [original theme](https://github.com/mtully/gitsome) uses parenthesis around the git branch instead of brackets around the whole prompt.

For full effect, use with [flat-terminal color scheme](https://github.com/KevinBongart/flat-terminal) and [zsh-syntax-coloring](https://github.com/zsh-users/zsh-syntax-highlighting).

## How to install

1. Download the theme into oh-my-zsh's custom themes directory:`$ mkdir -p $ZSH_CUSTOM/themes && curl https://raw.github.com/KevinBongart/gitsome/master/gitsome.zsh-theme -o $ZSH_CUSTOM/themes/gitsome.zsh-theme`
2. Set the theme in your .zshrc file: `ZSH_THEME="gitsome"`
3. For the nice colors, use [flat-terminal](https://github.com/KevinBongart/flat-terminal): [download here](https://github.com/KevinBongart/flat-terminal/archive/master.zip) then open "Flat.terminal"
