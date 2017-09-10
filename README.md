### Note: This is a fork of the [original collection of Arc themes for KDE Plasma](https://github.com/PapirusDevelopmentTeam/arc-kde) because transparent themes have been removed in the newer version. For the newer version, check out the original.

<p align="center">
  <img src="https://raw.githubusercontent.com/giogziro95/arc-kde/master/preview.png" alt="Preview Arc-Dark KDE"/>
  <sup><sub>Screenshot Details: Engine: <a href="https://github.com/tsujan/Kvantum/tree/master/Kvantum">Kavntum</a> | Kvantum Theme: Arc Dark Transparent | Aurorae decoration: Arc Dark Transparent | Color Scheme: Arc Dark | Icons: <a href="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme">Papirus Dark</a> | Dock: <a href="https://github.com/psifidotos/Latte-Dock">Latte Dock</a></sub></sup>
</p>

Arc KDE - This is a port of the popular [GTK theme Arc](https://github.com/horst3180/Arc-theme) for Plasma 5 desktop with a few additions and extras.

In this repository you'll find:

- Aurorae Themes
- Konsole Color Schemes
- Konversation Themes
- Kvantum Themes
- Plasma Color Schemes
- Plasma Desktop Themes
- Plasma Look-and-Feel Settings
- Wallpapers
- Yakuake Skins
- Extra tools

**NOTE:** Plasma theme Arc Color now supports KDE Color Schemes with [Papirus icon theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme).

## Installation

### Arc KDE Installer

Use the scripts to install the latest version directly from this repo (independently on your distro):

**NOTE:** Use the same script to update Arc-KDE.

#### ROOT directory

```
wget -qO- https://raw.githubusercontent.com/giogziro95/arc-kde/master/install-arc-kde-root.sh | sh
```
#### HOME directory

```
wget -qO- https://raw.githubusercontent.com/giogziro95/arc-kde/master/install-arc-kde-home.sh | sh
```

#### Remove

```
wget -qO- https://raw.githubusercontent.com/giogziro95/arc-kde/master/remove-arc-kde.sh | sh
```

## Recommendations

- For better looking please use this pack with [Kvantum engine](https://github.com/tsujan/Kvantum/tree/master/Kvantum).

  Run `kvantummanager` to choose and apply **Arc Dark Transparent** (or another) theme.

- Install [Papirus icon theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) for a more consistent and beautiful experience.

- Fix the color of the menubar on Arc Dark GTK theme:

  ```
  sudo sh ~/.local/share/plasma/desktoptheme/Arc-Dark/fix-menubar.sh
  ```

  ![Screenshot](fix-menubar.png)

## Extras

- [Firefox Theme](https://github.com/giogziro95/arc-kde/tree/master/extra/firefox) — patch for [Arc Dark Firefox Theme](https://github.com/horst3180/arc-firefox-theme#arc-dark-firefox)
- [Telegram Themes](https://github.com/giogziro95/arc-kde/tree/master/extra/telegram) — Arc KDE & Arc Dark KDE themes for [Telegram](https://desktop.telegram.org)
- [Nylas Skin](https://github.com/varlesh/Nylas-Arc-Dark-Theme) — Arc Dark theme for mail client [Nylas N1](https://github.com/nylas/nylas-mail)
- [VLC Skin](https://github.com/varlesh/VLC-Arc-Dark) — Arc Dark skin for [VLC](http://www.videolan.org/vlc/)
- [Eclipse Theme](https://github.com/giogziro95/arc-kde/tree/master/extra/eclipse) ­— Arc Dark Theme for [Eclipse IDE](https://eclipse.org/ide/)
- [KDE-gaps](http://www.simonizor.gq/kde-gaps) — a modification of Arc-Dark that removes the title, window buttons, and makes the window decorations completely transparent

## License

[GNU GPL v3](https://github.com/giogziro95/arc-kde/blob/master/LICENSE)
