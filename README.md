# MacOS ZSH Completions

This repository is a compilation of completions for MacOS found on various places throughout the internet. They are intended to provide completion for commands provided my MacOS like `tmutil`, `mdutil`, etc...

I found these when digging around Apples open-source [website](https://opensource.apple.com/source/zsh/zsh-84/).  

## Installation

### Oh My ZSH

Clone this repo into your `${ZSH_CUSTOM}` directory

```sh
git clone git@github.com:sticklerm3/mac-zsh-comps.git "$ZSH_CUSTOM/plugins/mac-zsh-comps"
```

Then edit your `~/.zshrc` and add it to your plugin array `plugins=(... mac-zsh-comps)`

Run `source ~/.zshrc` or restart your shell to use the new addition!
