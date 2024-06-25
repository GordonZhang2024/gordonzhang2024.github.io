<!--
.. title: How to install Hyprland on Fedora Linux
.. slug: how-to-install-hyprland-on-fedora-linux
.. date: 2024-06-02 09:31:21 UTC
.. tags: Linux
.. category: 
.. link: 
.. description: How to install Hyprland on Fedora Linux
.. type: text
-->

# How to install Hyprland on Fedora Linux
[Hyprland](https://hyprland.org/) is a famous tiling window mananger.
It has earned more than 14k stars on GitHub.

This passage will tell you how to install it on Fedora.

## Installation
Use dnf to install it:
```bash
$ sudo dnf install hyprland kitty
```
*Kitty is a terminal. you'll need it when using hyprland.*
When the installation is completed, let's try it.

## Try
First, switch to a tty of your machine. For example, `ctrl+alt+F3` will switch to tty3.
Enter your username and password, then you will see the bash console.
Next, type command:
```bash
$ Hyprland
```

You will see hyprland in a few seconds.

But you will also see a warning. It will tell you that you are using a default config file.
It will also tell you some keyboard shortcuts. You can try these keyboard shortcuts.
## How to disable the warning
Use any editor to edit the config file which is shown in the warning(for example, `~/.config/hypr/hyprland.conf`,
 You will see a line that says something like `delete this line to disable the warning.`

Just delete this line!

## Configuration
You need to follow [hyprland wiki](https://wiki.hyprland.org/Configuring/Configuring-Hyprland/)

> Important
Some Hyprland plugins only supports Arch based Linux Distributions or nixos.

## That's all
You have sucessfully installed hyprland.
**I hope you can enjoy using it :)**

