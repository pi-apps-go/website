---
title: Install Webcord on Nvidia Jetson | Pi-Apps
description: Install Webcord on Nvidia Jetson using Pi-Apps
---
<div class="simple-install-content content">

# Install <img src="/img/app-icons/Webcord/icon-64.png" height=24> Webcord on <img src=/img/other-icons/nvidia-icon.svg height=24> Nvidia Jetson

## <img src="/img/app-icons/Webcord/icon-64.png"> Webcord
> Fast Discord client for ARM that mimics the official Discord client.
> The app runs independent to chromium and can be hidden to the system tray unlike other solutions out there.
> To run: Menu -> Internet -> WebCord.
> To run in a terminal: webcord
> This client is not officially provided or supported by Discord and technically violates ToS, use at your own risk
> Made by SpacingBat3 on Github with care :)

Fortunately, Webcord is very easy to install on your Nvidia Jetson in just two steps.
1. Install Pi-Apps - the best app installer for Nvidia Jetson.
2. Use Pi-Apps to install Webcord.
</div>
<div class="simple-install-content content">

## Compatibility
For the best chance of this working, we recommend using the latest version of [Nvidia Jetpack](https://developer.nvidia.com/embedded/jetpack-archive) for your specific Jetson (Jetson Xavier, or Jetson Orin).
Webcord will run on L4T Ubuntu ARM64.
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

## Install Webcord

Now that you have Pi-Apps installed, it is time to install Webcord.
First launch Pi-Apps from your start menu:
<img src="/img/start-menu.png">
Then click on the <b>Internet</b> category, which leads to the <b>Communication</b> category.
<img src="/img/category-selections/Communication.png">
Now scroll down to find <b>Webcord</b> in the list.
<img src="/img/app-icons/Webcord/app-selection.png">
Just click Install and Pi-Apps will install Webcord for you!
</div>
<div class="simple-install-content content">

Pi-Apps is a free and open source tool made by [Botspot, theofficialgman, and other contributors](/about/#contributors). Find out more at https://pi-apps.io
</div>
