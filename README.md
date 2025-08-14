![Setup Guide](https://img.shields.io/badge/Setup-Guide-blue.svg)
# Manual Installation for .tar Applications

> Tested on Linux Mint Cinnamon. For distro like Ubuntu, debian packages should be used.

<br>

1. Download the desired .tar package and locate it.
  - You can move the downloaded file first.
<br>
2. extract the file

```bash
tar -xvzf appname.tar.gz
```

then go to its folder
cd appname


Run the main executable file. it's often inside a bin folder or similar folder. test run by clicking it or using terminal
./appname


create a .desktop file and edit it
nano ~/.local/share/applications/appname.desktop
