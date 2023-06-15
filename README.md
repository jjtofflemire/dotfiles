# KDE-Customization

Quick ricing instructions for me when I forget about everything I did (yes I know its pretty mild, I just don't want to have to restart everything from memory on a reinstall)

## Files

- [/etc/ly/config.ini](config.ini)
- [/etc/vconsole.conf](vconsole.conf)
- [/home/andya/.bashrc](.bashrc)
- [/home/andya/kitty-gruvbox-theme/gruvbox_dark_hard.conf](gruvbox_dark_hard.conf)
- [/home/andya/kitty/kitty.conf](kitty.conf)

## Themes

## Cursor

- I use Posy's Cursor pack

- Install from [the Github](https://github.com/simtrami/posy-improved-cursor-linux) instead of through the KDE store

### KDE Global Theme

- [Gruvbox theme from KDE store](https://store.kde.org/p/1327723) (I think)

  - This theme pack should edit every theming category in `KDE Settings` > `Appearance`

  - Konsole theme is the same, just add the theme in a profile

### Kitty

- Uses the gruvbox theme with `/home/andya/kitty-gruvbox-theme/gruvbox_dark_hard.conf`

- Uses FiraMono Nerd Font

### Ly

- I use [Ly](https://github.com/fairyglade/ly) as my window manager

- I use custom colors using [mkinitcpio-colors](https://github.com/evanpurkhiser/mkinitcpio-colors) by adding colors to `vconsole.conf`

  - To add the colors to `initramfs`, I used `sudo mkinitcpio -p linux-zen`