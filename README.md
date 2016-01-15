.aliases
========

- [Aliases for bash and git](#aliases-for-bash-and-git)
- [Installation](#installation)
- Started with passion by [AlgoTech](http://www.algotech.solutions)

## Aliases for bash and git

#### Bash aliases for:
  - *Git* - [aliases](doc/bash/git_aliases.md)
  - *GitHub* - [aliases](doc/bash/github_aliases.md)
  - *Composer* - [aliases](doc/bash/composer_aliases.md)
  - *Vim* - [aliases](doc/bash/vim_aliases.md)
  - *Bash* - [aliases](doc/bash/bash_aliases.md)
  - *Symfony* - [aliases](doc/bash/symfony_aliases.md)
  - *PHPUnit* - [aliases](doc/bash/phpunit_aliases.md)
  - *Cordova* - [aliases](doc/bash/cordova_aliases.md)

#### Git aliases
  - **co**: checkout
  - **graph**: log --color --graph --pretty=format:\"%h | %ad | %an | %s%d\" --date=short
  - **hist**: log --color --pretty=format:\"%C(yellow)%h%C(reset) %s%C(bold red)%d%C(reset) %C(green)%ad%C(reset) %C(blue)[%an]%C(reset)\" --relative-date --decorate
  - **restore**: checkout --
  - **unstage**: reset HEAD --

## Installation

Clone it into `.aliases` folder in your home directory:
```bash
cd ~
git clone https://github.com/algotech/dotaliases.git .aliases
```

To enable bash aliases: add to `~/.bash_profile` or `~/.profile`:
```bash
source ~/.aliases/bash_aliases
```

To enable git aliases: add to `~/.gitconfig`:
```bash
[include]
    path = ~/.aliases/git_aliases
```

Required commands:
 - [hub](https://hub.github.com)

