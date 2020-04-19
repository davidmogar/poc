```
sudo pacman -S lightdm-webkit2-greeter
git clone https://github.com/davidmogar/poc.git
sudo mv poc /usr/share/lightdm-webkit/themes
```

Edit `/etc/lightdm/lightdm-webkit2-greeter.conf` and set `webkit_theme` to `poc`.

To show the font working:
```
chromium /usr/share/lightdm-webkit/themes/index.html
```

To render with lightdm:
```
lightdm-webkit2-greeter
```
