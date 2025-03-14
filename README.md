# Legacy Bourne Shell
*A modern Linux port of the Bourne Shell (`/bin/sh`) from UNIX v7 of 1977*

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
cd ..
rm -rf heirloom-sh
```

Probably to semi-uninstall on most Linux systems:

```console
sudo ln -sfn /bin/bash /bin/sh
```

Probably to semi-uninstall on Ubuntu:

```console
sudo ln -sfn /bin/dash /bin/sh
```

Then fully remove the binary:

```console
sudo rm /usr/local/bin/sh
```
