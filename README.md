# Terminal-Config

## 🛠️ Required Packages
Install these to make the aliases and visuals work:

```
# pacman -S eza blesh fastfetch
```

## ⚡ Terminal Features
* **ble.sh**: Syntax highlighting and auto-suggestions for Bash.
* **eza**: A replacement for `ls` with icons.
  * Alias: `ls` -> `eza --icons --group-directories-first`
* **fastfetch**: System information display on startup.

## 🚀 Restore Procedure
1. alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
2. git clone --bare https://github.com/stevandis/terminal-config.git $HOME/.cfg
3. config checkout
4. config config --local status.showUntrackedFiles no
