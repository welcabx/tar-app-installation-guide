![Setup Guide](https://img.shields.io/badge/Setup-Guide-blue.svg)
# Manual Installation for .tar Applications
Tested on Linux Mint Cinnamon. For distro like Ubuntu, debian packages should be used.<br><br><br>

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
<br><br>
4. Create a .desktop file
```bash
nano ~/.local/share/applications/appname.desktop
```
<br><br>
5. Paste the following inside the app's .desktop file.
```ini
[Desktop Entry]
Version=1.0
Name=App Name
Exec=/home/yourusername/path/to/app/executable
Icon=/home/yourusername/path/to/app/icon.png
Type=Application
Categories=Utility;
Terminal=false
```
<br><br>
6. Make it executable
```bash
chmod +x ~/.local/share/applications/appname.desktop
```
<br><br>
7. Refresh desktop database
```bash
update-desktop-database ~/.local/share/applications
```
<br><br>
8. Launch and pin. Search it on the app drawer, right click on it and then "add to favorites".
