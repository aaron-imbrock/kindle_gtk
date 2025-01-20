# kindle_gtk




###

Kindle-sdk requires `meson >=1.1`. That can be installed from Debian Backports: `sudo apt install -t bookworm-backports meson`

`$ cat /etc/apt/sources.list.d/sources.list`
```
deb http://mirrors.wikimedia.org/debian/ bookworm main contrib non-free non-free-firmware
deb http://security.debian.org/debian-security bookworm-security main contrib non-free non-free-firmware
deb http://mirrors.wikimedia.org/debian/ bookworm-updates main contrib non-free non-free-firmware
# Debian Backports - https://backports.debian.org/Instructions/
# Install
# apt install -t bookworm-backports <package>
# Search
# apt search <package>
# xdiskusage/stable-backports 1.60-4~bpo12+1 amd64
# Search for all python packages from backports:
# apt search . | grep -E 'bpo12|stable-backports' | grep -i python
deb http://deb.debian.org/debian bookworm-backports main contrib non-free-firmware
```
