---
title: Install Caprine on Nvidia Jetson | Pi-Apps
description: Install Caprine on Nvidia Jetson using Pi-Apps
---
<div class="simple-install-content content">

# Install <img src="/img/app-icons/Caprine/icon-64.png" height=24> Caprine on <img src=/img/other-icons/nvidia-icon.svg height=24> Nvidia Jetson

## <img src="/img/app-icons/Caprine/icon-64.png"> Caprine
> Caprine is an unofficial and privacy focused Facebook Messenger app with many useful features. 
> Built with Electron, Caprine features a Dark mode, keyboard shortcuts, ability to toggle last seen/typing indicators, work chat support, code blocks, custom text size, and an interface that adapts to resizing windows.
> 
> Caprine is a third-party app and is not affiliated with Facebook. 
> 
> To run: Menu -> Internet -> Caprine
> To run in a terminal: /opt/Caprine/caprine

Fortunately, Caprine is very easy to install on your Nvidia Jetson in just two steps.
1. Install Pi-Apps - the best app installer for Nvidia Jetson.
2. Use Pi-Apps to install Caprine.
</div>
<div class="simple-install-content content">

## Compatibility
For the best chance of this working, we recommend using the latest version of [Nvidia Jetpack](https://developer.nvidia.com/embedded/jetpack-archive) for your specific Jetson (Jetson Xavier, or Jetson Orin).
Caprine will run on L4T Ubuntu ARM64.
</div>
<div class="simple-install-content content">

## Install Pi-Apps

Pi-Apps is a free tool that makes it incredibly easy to install the most useful programs on your Nvidia Jetson with just a few clicks.

Open a terminal and run this command to install Pi-Apps:
```bash
wget -qO- https://raw.githubusercontent.com/Botspot/pi-apps/master/install | bash
```
Feel free to check out the Pi-Apps source code here: https://github.com/Botspot/pi-apps
</div>
<div class="simple-install-content content">

## Install Caprine

Now that you have Pi-Apps installed, it is time to install Caprine.
First launch Pi-Apps from your start menu:
<img src="/img/start-menu.png">
Then click on the <b>Internet</b> category, which leads to the <b>Communication</b> category.
<img src="/img/category-selections/Communication.png">
Now scroll down to find <b>Caprine</b> in the list.
<img src="/img/app-icons/Caprine/app-selection.png">
Just click Install and Pi-Apps will install Caprine for you!
</div>
<div class="simple-install-content content">

Pi-Apps is a free and open source tool made by [Botspot, theofficialgman, and other contributors](/about/#contributors). Find out more at https://pi-apps.io
</div>
