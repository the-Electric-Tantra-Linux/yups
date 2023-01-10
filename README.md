# [yups](https://github.com/the-Electric-Tantra-Linux/yups)

A [fzf](https://github.com/junegunn/fzf) TUI for [paru](https://github.com/Morganamilo/paru)

Latest Release 1.0.0

# Usage

```text
❯ ./yups -h

╔════════════════════╗
║░      yups      ░║
╚════════════════════╝

usage: yups -sqrmfy {args} -hv
path: /usr/bin/yups

   -s, -style             select [(l|light)|(m|mono)(p|paper)]
   -q, -query             input starting search query
   -r, -repository        browse a specific repo [core|extra|community|aur]
   -m, -margin            set the margin 10|2,5|5,3,8|1,5,2,3
   -h, -help              show this help
   -v, -version           get yups version

   ctrl-space             toggle package
   ctrl-d                 deselect-all
   ctrl-l                 clear-query
   ctrl-p                 toggle-preview
   ctrl-w                 toggle-preview-wrap
   shift-up               preview-up
   shift-down             preview-down
   shift-left             preview-page-up
   shift-right            preview-page-down
   ctrl-s                 see package stats
   ctrl-u                 list updatable packages
   ctrl-n                 read the news
   ctrl-g                 get info about installed packages
   enter                  install package(s)
   esc                    leave, do nothing
   tab                    toggle package and move pointer down
   shift-tab              toggle package and move pointer up
   ctrl-h                 list keybindings (help)
```

# Requirements

- [fzf](https://github.com/junegunn/fzf)
- [paru](https://github.com/morganamilo/paru)
- bash

# Installation

## Arch Linux

```
paru -S yups
```

## From Source

```sh
git clone https://github.com/the-Electric-Tantra-Linux/yups.git
cd yups
sudo make install
```

## Direct Download

```sh
wget -O ~/.local/bin/yups https://raw.githubusercontent.com/the-Electric-Tantra-Linux/yups/main/yups
chmod +x ~/.local/bin/yups
```
