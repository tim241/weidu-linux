# Weidu Linux script

this script symlinks all files/folders with uppercase letters in them to lowercase files/folders

it makes installing mods on linux with weidu easier (due to it not requiring a ntfs image/other tricks)

# Requirements
* Weidu

# Installation
```
git clone https://gitlab.com/tim241/weidu-linux
install -D -m=0775 weidu-linux/weidu-linux /usr/bin/weidu-linux
```

# Usage
exactly the same as weidu, because it invokes weidu itself

# Env Variables
```
WEIDU_NOCLEAN
=============
Default: 0
Enabled: 1

when enabled, weidu-linux will not remove the symlinks after symlinking
```

