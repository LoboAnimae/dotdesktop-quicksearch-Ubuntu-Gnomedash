# Desktop Dash Templates

## What is this?

This is a small, open source repository meant to store different `.desktop` files that allow for applications to appear in the Dash search in **Gnome Desktop**. All files assume that the executable for a file (such as a `.appimage`) is under the directory `/usr/bin`.

For example, given a `.desktop` file for Telegram (such as `/usr/share/applications/Telegram.desktop`), there will be an icon for it under `/opt/Telegram/telegram.png` and an executable under `/usr/bin/telegram.appimage` (or any other extension, as long as it is executable). More of this can be seen under the **How to Install** section down below.

## What Can I Do?

Honestly? It's just a small repository I created because I am waaaaaay too lazy as to keep writing these files with every distro hop I do :P

Feel free to add any new items, but try to keep them on the same directories as I do. Please add an internal `README.md` in case you need to give more information about a specific item.

**Please make it so that any added icon is of type PNG**

## How to Install

First, check if the application you want to add is already under the `desktop` folder. If not, you can try to create one and add it! I used [this](https://askubuntu.com/questions/281293/creating-a-desktop-file-for-a-new-application) question to help me create the ones I added :)

If the file is actually there, download it, along with the icon inside the `icon` directory. Do not forget about the fact that you need the actual `.appimage` or executable! These **CANNOT** be found inside this repository.

Finally, in the case of Ubuntu Gnome, just move the `.desktop` file into the `/usr/share/applications/` directory and the icon to the directory specified inside the `Icon` parameter inside the `.desktop` file.

And that's it! Depending of your distro, you might need to log out/reboot your computer, but it should be in there the next time you look it up!
