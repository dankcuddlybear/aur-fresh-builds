# aur-fresh-builds
AUR (Arch User Repository) software packages updated daily. Contains various useful open-source gaming and productivity software that I use on a daily basis, that is not available in the official Arch repositories or Chaotic-AUR.

To add this repository, add the following to `/etc/pacman.conf`:
```
[aur-fresh-builds]
SigLevel = PackageOptional
Server = https://github.com/dankcuddlybear/aur-fresh-builds/raw/refs/heads/main/
```
