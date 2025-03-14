# Legacy Bourne Shell
*For modern Linux systems*

A port of the legacy Bourne Shell (`/bin/sh`) from UNIX v7 of 1977.

This repo is a fork with updates for compiling on modern Linux platforms.

Dependency packages:

```console
git base-devel gcc make
```

Install instructions (for `/bin/sh -> /usr/local/bin/sh`)

```console
git clone https://github.com/JesseSteele/heirloom-sh.git
cd heirloom-sh
make
sudo make install
sudo ln -sfn /usr/local/bin/sh /bin/sh
```
