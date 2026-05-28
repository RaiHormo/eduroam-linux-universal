# Eduroam Linux Universal Installer
An easy to use eduroam installer for Linux that works for any University.

A fork from the official CAT installer that's been made easier to use.

Made by Iris Hormoviti
## Download
| [AppImage (Easier)](https://github.com/RaiHormo/eduroam-linux-universal/releases/latest/download/Eduroam-Linux-Installer.AppImage) | [Python Script](https://github.com/RaiHormo/eduroam-linux-universal/releases/latest/download/eduroam-universal.py) |
|-------------------|---------------|
## How to run
1. Download one of the files.
2. Right click it in your file manager, go to Properties
3. Make sure "Execute as Program" is enabled.
4. Now right click it, and click "Run as program". The installer should now launch.

If the AppImage doesn't work, try using the python script.
### Run Python Script
You can run the python script in the same way as the AppImage usually, but it can also be run like this from the terminal:

Open a terminal, type `python3 ` (with a space after), then drag and drop the python file into the terminal window. Then press enter.

Alternatively you can type `python3 /path/to/the/file/eduroam-universal.py`.
## How to use
**The script requires an internet connection to fetch the data for each institution.** 
You can use a mobile hotspot or ethernet temporarily if in the university.

When it opens, you're greeted with a list of institutions. Just start typing to search through them, and select the one you're in.

After that you will see some information about your institution, make sure it's correct.

Then you will be asked for a username, and password.

For the username, it should be formatted as `username@example.com` like an email. 
Don't add things like the department or other subdomains in the username like `@go.example.com` or `@o365.example.com`.

Just click OK, and the network should be saved. You can connect to it in your desktop settings like normal.
## dbus Error
If you get an error about dbus when running it, try running the python script with `/usr/bin/python3` before the file path. Otherwise, your distro might not use NetworkManager at all.

If there is an issue, please report it here.
