# arch-repo

Custom Pacman repository with non-official packages for Arch Linux.

Installation:

- Add this to ```/etc/pacman.conf```:

```
[project-repo]
SigLevel = Optional TrustAll
Server = https://raw.githubusercontent.com/wardgauderis/arch-repo/master
```
- ```sudo pacman -Sy```
