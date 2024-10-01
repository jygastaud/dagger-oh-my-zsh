# dagger-oh-my-zsh

Dagger plugin for oh-my-zsh

## Installation

### [Oh-My-Zsh](http://ohmyz.sh/)

```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/jygastaud/dagger-oh-my-zsh.git dagger
```

Enable it by adding _dagger_ to the [_plugins array_](https://github.com/robbyrussell/oh-my-zsh/blob/master/templates/zshrc.zsh-template#L66).

You have to restart your current terminal in order to use the aliases below.

```
# located under $HOME/.zshrc
plugins=(git dagger)
```

### [Antigen](https://github.com/zsh-users/antigen)

Add `antigen bundle jygastaud/dagger-oh-my-zsh@main` to your `.zshrc` file. Antigen will handle cloning the plugin for you automatically the next time you start `zsh`. You can also add the plugin to a running ZSH with `antigen bundle jygastaud/dagger-oh-my-zsh@main` for testing before adding it to your `.zshrc`.


### [Zgen](https://github.com/tarjoilija/zgen)

**Need to be tested**

Add `zgen load jygastaud/dagger-oh-my-zsh` to your `.zshrc` file in the same function you're doing your other `zgen load` calls in. Zgen will automatically clone the repository for you when you do a `zgen save`, and load it the next time you start a terminal session.


## Update autocomplete script

`make update-autocomplete`

