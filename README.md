# Apple Emoji on GNOME 49
This is a guide how to download Apple Emoji on GNOME 49

### 1. Install Apple Emoji Font
You can install any. I prefer to use [Apple Emoji for Linux](https://github.com/samuelngs/apple-emoji-linux).
After installing it create a directory `~/.local/share/fonts` and copy font there.
### 2. Delete Noto Color Emoji
We will use the easiest way to delete it. 
On Fedora use:
```
sudo dnf remove google-noto-emoji-color-fonts
```
On Ubuntu-like use:
```
sudo apt remove fonts-noto-color-emoji
```
> **_NOTE:_** If you have other distro do this step yourself
### 3. Refresh fonts and GNOME
Enter `fc-cache -f -v` in console and restart GNOME.
That's it! ✌️
