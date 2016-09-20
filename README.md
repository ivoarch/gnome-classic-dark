INSTALL DEPENDENCIES
-------

```
# yum install gnome-classic-session
```

BACKUP ORIGINAL THEME
------

```
# cp /usr/share/gnome-shell/theme/gnome-classic.css gnome-classic.css.bak
# cp /usr/share/gnome-shell/extensions/window-list@gnome-shell-extensions.gcampax.github.com/classic.css classic.css.bak
```

REPLACE WITH GNOME CLASSIC DARK THEME
------------------------------

```
$ git clone https://github.com/ivoarch/gnome-classic-dark
$ cd gnome-classic-dark/
# cp gnome-classic-dark.css /usr/share/gnome-shell/theme/gnome-classic.css
# cp classic-dark.css /usr/share/gnome-shell/extensions/window-list@gnome-shell-extensions.gcampax.github.com/classic.css
```

RESTART GNOME
------------

Press **Alt+F2** type **r** or **rt** .

ENJOY!
-----

![preview](http://storage2.static.itmages.ru/i/16/0920/h_1474401985_5678384_94e21531f8.png)
