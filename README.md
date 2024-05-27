# zsh-tenv

tenv autocompletion plugin for zsh

## How to install

### Simple ZSH

Clone the repository and source the [tenv.plugin.zsh](tenv.plugin.zsh)

```
git clone https://github.com/tofuutils/zsh-tenv
source zsh-tenv/tenv.plugin.zsh
```

To make this changes permanent, either add `source /path/to/tenv.plugin.zsh` or 
copy the contents of [tenv.plugin.zsh](tenv.plugin.zsh) to your .zshrc

### As Oh My zsh plugin

Clone this repositoriy into your oh my zsh plugins directory

```
git clone https://github.com/tofuutils/zsh-tenv /path/to/myzsh/plugins
```

add the plugin to your .zshrc plugins array 

```
plugins=(... tenv)
```

### How to update 

If you are using simple ZSH, repeat the install process. 

if you are using as oh my zsh plugin, cd into tenv plugin directory and git pull

```
cd /path/to/ohmyzsh/plugins/tenv
git pull origin main
```
