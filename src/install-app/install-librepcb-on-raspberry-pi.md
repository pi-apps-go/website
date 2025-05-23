---
title: Install LibrePCB on Raspberry Pi | Pi-Apps
description: Install LibrePCB on Raspberry Pi using Pi-Apps
---
<div class="simple-install-content content">

# Install <img src="/img/app-icons/LibrePCB/icon-64.png" height=24> LibrePCB on <img src=/img/other-icons/raspberrypi-icon.svg height=24> Raspberry Pi

## <img src="/img/app-icons/LibrePCB/icon-64.png"> LibrePCB
> LibrePCB is a free, cross-platform, easy-to-use electronic design automation suite to draw schematics and design printed circuit boards – for makers, students and professionals, from beginners to experts.
> 
> This software just lets you develop electronics the right way. No costs. No restrictions. No online account. No unnecessary complexity.
> To run: Menu -> Programming -> LibrePCB
> To run in a terminal: flatpak run --file-forwarding org.librepcb.LibrePCB

Fortunately, LibrePCB is very easy to install on your Raspberry Pi in just two steps.
1. Install Pi-Apps - the best app installer for Raspberry Pi.
2. Use Pi-Apps to install LibrePCB.
</div>
<div class="simple-install-content content">

## Compatibility
For the best chance of this working, we recommend using the latest version of [Raspberry Pi OS](https://www.raspberrypi.com/software/), which is currently version **Bookworm**.
Raspberry Pi OS has 32-bit and 64-bit variants, both of which will run on most Raspberry Pi computers, including the Pi 3, Pi 4, and Pi5.
**LibrePCB will only run on PiOS 64-bit.** Pi-Apps will not let you install LibrePCB on PiOS 32-bit.
</div>
<div class="simple-install-content content">

## Install Pi-Apps

Pi-Apps is a free tool that makes it incredibly easy to install the most useful programs on your Raspberry Pi with just a few clicks.

Open a terminal and run this command to install Pi-Apps:
```bash
wget -qO- https://raw.githubusercontent.com/Botspot/pi-apps/master/install | bash
```
Feel free to check out the Pi-Apps source code here: https://github.com/Botspot/pi-apps
</div>
<div class="simple-install-content content">

## Install LibrePCB

Now that you have Pi-Apps installed, it is time to install LibrePCB.
First launch Pi-Apps from your start menu:
<img src="/img/start-menu.png">
Then click on the <b>Engineering</b> category.
<img src="/img/category-selections/Engineering.png">
Now scroll down to find <b>LibrePCB</b> in the list.
<img src="/img/app-icons/LibrePCB/app-selection.png">
Just click Install and Pi-Apps will install LibrePCB for you!
</div>
<div class="simple-install-content content">

Pi-Apps is a free and open source tool made by [Botspot, theofficialgman, and other contributors](/about/#contributors). Find out more at https://pi-apps.io
</div>
