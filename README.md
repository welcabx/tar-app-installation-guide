![Setup Guide](https://img.shields.io/badge/Setup-Guide-blue.svg)
# Manual Installation for .tar Applications
### Tested on Linux Mint Cinnamon. For distro like Ubuntu, debian packages should be used.
<br><br>
1. Locate the tar file you downloaded and extract it.
```bash
tar -xvzf appname.tar.gz
```
<br><br>
2. Go inside the extracted directory.
```bash
cd appname
```
<br><br>
3. Run the main executable file. It is often inside the root, bin or similar folder.
You can test it by running:
```bash
./appname
```
4. Create a .desktop file
```bash
nano ~/.local/share/applications/appname.desktop
```
