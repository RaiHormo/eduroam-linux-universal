# Eduroam Linux Universal Installer
An easy to use eduroam installer for Linux that works for any University.

A fork from the official CAT installer that's been made easy to use.

Made by Iris Hormoviti
## Download
### AppImage (Easier)
[Click here to download the AppImage file](https://a)

Download the file and just double click to run it.

If it doesn't run, right click it, go to Properties, and make sure "Execute as Program" is enabled.
If that still doesn't work, maybe your distro doesn't have the FUSE library, in which case, you should use the python file
### Python
[Click here to download the Python file](https://a)

Open a terminal, type `python3 ` (with a space after), then drag and drop the python file into the terminal window. Then press enter.
Alternatively you can type `python3 /path/to/the/file/eduroam-universal.py`
## How to use
**The script requires an internet connection to fetch the data for each institution.** 
You can use a mobile hotspot or ethernet temporarily if in the university.

When it opens, you're greeted with a list of institutions. Just start typing to search through them, and select the one you're in.

After that you will see some information about your institution, make sure it's correct.

Then you will be asked for a username, and password.

For the username, it should be formatted as `username@example.com` like an email. 
Don't add things like the department or other subdomains in the username like `@go.example.com` or `@o365.example.com`.

Just click OK, and the network should be saved. You can connect to it in your desktop settings like normal.

If there is an issue, please report it here.
