# arch-repo

Custom Pacman repository with non-official packages for Arch Linux.

Installation:

```shell
$ sudo echo -e "[project-repo]\nSigLevel = Optional TrustAll\nServer = https://raw.githubusercontent.com/WardGauderis/arch-repo/master" >> /etc/pacman.conf
$ sudo pacman -Sy
```
