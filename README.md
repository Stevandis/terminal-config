# Terminal-Config

My terminal config

## Required Packages
Install these to make the aliases and visuals work:

#### 1. Download oh-my-bash
```
$ bash -c "$(curl -fsSL https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh)"
```

#### 2. Install Packages
```
# pacman -S eza blesh fastfetch
```

## Terminal Features
* **ble.sh**: Syntax highlighting and auto-suggestions for Bash.
* **eza**: A replacement for `ls` with icons.
* **fastfetch**: System information display on startup.

## Restore Procedure
1. alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
2. git clone --bare https://github.com/stevandis/terminal-config.git $HOME/.cfg
3. config checkout
4. config config --local status.showUntrackedFiles no
