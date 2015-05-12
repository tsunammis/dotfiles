# Personal dot files

### Installation

```bash
cd ~
git clone https://github.com/tsunammis/dotfiles.git .dotfiles
```

At this moment, nothing is happening, see below to decide what you want to integrate to your bash environment.

### Add sexy bash prompt

```bash
echo '. ~/.dotfiles/.bash_prompt' >> .bashrc
```

### Add useful command

```bash
echo '. ~/.dotfiles/.bash_whaa' >> .bashrc
```

* **top10** - _Top 10 commands_
* **dirsize** - _Finds directory sizes and lists them for the current directory_
* **fared** - _Find and removed empty directories_
* **farad** - _Find and removed all dotfiles_
* **up** - _Goes up many dirs as the number passed as argument, if none goes up by 1 by default_

### Add a lot alias

```bash
echo '. ~/.dotfiles/.bash_alias' >> .bashrc
```

### Add git shortcuts

```bash
echo '. ~/.dotfiles/.bash_git' >> .bashrc
```

### Warnings

**These commands works fine on MacOSX, never tried on another system.**

To improve the user experience, you should install *bash-completion* from *[homebrew](http://brew.sh/)*

```bash
brew install bash-completion
echo '. ~/.dotfiles/.bash_completion' >> .bashrc
brew tap homebrew/completions
```
