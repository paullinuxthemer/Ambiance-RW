# Ambiance-RW

a GTK2,and GTK3 file for the Gnome-desktop

![s](https://cn.pling.com/img/2/7/d/0/6f957fb9fc7e6d4099d71f5c3289e15f1efa.jpg)


This is a re-interpretation of the Ambiance-theme.

The changes are made with respect for the way it was written: this means changing colors in 'main.gtk.CSS' will have no advers effect on the changes I've made.

I've only redone the GTK 3.20 file, so the changes are only visible in a gnome 3.20+ (yes, also 3.28) environment (including ubuntu 18.04).

There are 4 versions available:

### Ambiance-RW
### Ambiance-RW-blue
### Ambiance-RW-DS 
### Ambiance-RW-DS-blue

The original Ambiance theme is part of Canonical official themes (https://launchpad.net/ubuntu-themes)
and has the license GNU GPL v3, Creative Commons - Attribution Share Alike

The themes presented here are in no way affiliated with the official Ambiance theme. 

When, as such, theming does not look the way it should be: make sure you have installed the necessary theme-"engines"

### GTK2 ENGINES REQUIREMENT

- GTK2 engine Murrine
- GTK2 engine Pixbuf

Fedora/RedHat distros:
> yum install gtk-murrine-engine gtk2-engines

Ubuntu/Mint/Debian distros:
> sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf

ArchLinux:
> pacman -S gtk-engine-murrine gtk-engines

### How to install:

Extract and put it into the themes directory i.e. ~/.themes/ or /usr/share/themes/ (create it if necessary).Then change the theme via distribution specific tool like Gnome tweak tool or Unity tweak tool, etc. (If you use Snap-packages instead of app's from the normal repositories than definitely put the theme to /usr/share/themes/.

