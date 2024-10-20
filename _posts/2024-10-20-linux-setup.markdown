---
layout: post
title:  "My Linux Setup"
date:   2024-10-20 13:00:00 -0400
categories: linux
---

![Arch Linux Screenshot](/assets/images/arch-screenshot.png)

## Base OS - Arch Linux

I use Arch Linux for all my laptops and desktops, because of it's highly customizable for my needs, and Arch Wiki is the best Wiki about Linux that I've used.
Together, it makes understanding my setup and potential troubleshooting very easy.

## Disks Setup

For all my laptops and desktops, I use one `/boot` partition and one LUKS encrypted partition, with LVM ontop of LUKS.

## GUI

Currently I have Nvidia GPU on my machines, so I use [PRIME](https://wiki.archlinux.org/title/PRIME) for hybrid setup and proprietary drivers directly on my desktops.

For Gnome DE on top of Xorg which currently works pretty well for me. [Flat Remix](https://drasite.com/flat-remix-gnome) themes for my Gnome Shell, GTK, Icon.

## Dev Tools

* Terminal: [WezTerm](https://wezfurlong.org/wezterm/index.html), the best terminal I've used, with very detailed docs and intuitive config using Lua.
* Editor: Emacs with [Spacemacs](https://www.spacemacs.org/), easily configure, with all the flexibility of regular Emacs.
* Shell: Zsh with [Oh My Zsh](https://ohmyz.sh/), good looking, tons of plugins available.
  * [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions): very easy to use completion tool, same keybinding as Emacs.
  * [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting): syntax highlighting for my shell commands.

You can view all my dotfiles config at my [dotfiles repo](https://github.com/WallyYang/dotfiles).
