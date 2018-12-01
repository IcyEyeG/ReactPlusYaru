# ReactPlusYaru theme for Linux

ReactPlusYaru is a fork [Yaru](https://github.com/ubuntu/yaru), which is going to be the default theme for Ubuntu, based on the color presets of the [ReactPlus!](https://github.com/IcyEyeG/ReactPlus) project.

It contains:
 * a GNOME Shell theme (at the moment, the same as Yaru);
 * a GTK2 (at the moment, the same as Yaru and [Yaru-dark](https://github.com/ubuntu/yaru/tree/gtk2-dark));
 * a collection of GTK3 theme presets, in both light and dark variants of all ReactPlus! color schemes. Yaru design was modified to incorporate the color variables of the classic [Windows Theme File Format](https://docs.microsoft.com/en-us/windows/desktop/controls/themesfileformat-overview). [Initial Unity support](https://github.com/ubuntu/yaru/tree/unity7) is also provided.

## Build and install themes from source

> Please note that by installing ReacPlusYaru **70 new themes will be added to your system**

This installation method is to try out the theme while developing it.

```bash
# Download the repository from github
git clone https://github.com/IcyEyeG/ReactPlusYaru.git
cd yaru
# Initialize build system (only required once per repo)
meson build
cd build
# Build and install
sudo ninja install
```

## Todo list:

 * Add Metacity, Unity and XFWM4 themes;
 * Implement ReactPlus! color presets on GNOME Shell, GTK2, Metacity, Unity and XFWM4 themes;
 * Add ReactPlus! assets, as they become available (wallpapers, icons, cursors, sounds, etc.).

Pull requests, forks, bug reports/fixes welcome!

## Copying or Reusing

Included scripts are free software licensed under the terms of the [GNU General Public License, version 3](https://www.gnu.org/licenses/gpl-3.0.txt).
