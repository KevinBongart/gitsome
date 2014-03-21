![screenshot](https://raw.github.com/KevinBongart/gitsome/master/screenshot.png)

This fork of Matt's [nice and simple oh-my-zsh prompt](https://github.com/mtully/gitsome) uses parenthesis around the git branch instead of brackets around the whole prompt.

It's a super simple prompt with some git:

1. The current directory
2. Current git branch name
3. Git status on the current branch (red/green)

For full effect, use [flat-terminal color scheme](https://github.com/KevinBongart/flat-terminal) and [zsh-syntax-coloring](https://github.com/zsh-users/zsh-syntax-highlighting).

## How to install

1. Download the theme into oh-my-zsh's custom themes directory:`$ mkdir -p $ZSH_CUSTOM/themes && curl https://raw.github.com/KevinBongart/gitsome/master/gitsome.zsh-theme -o $ZSH_CUSTOM/themes/gitsome.zsh-theme`
2. Set the theme in your .zshrc file: `ZSH_THEME="gitsome"`
3. For nicer colors, use [flat-terminal](https://github.com/KevinBongart/flat-terminal): [download](https://github.com/KevinBongart/flat-terminal/archive/master.zip) then open "Flat.terminal"
