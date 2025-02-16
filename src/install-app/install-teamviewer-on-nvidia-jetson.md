---
title: Install TeamViewer on Nvidia Jetson | Pi-Apps
---
<div class="simple-install-content content">

# Install <img src="/img/app-icons/TeamViewer/icon-64.png" height=24> TeamViewer on <img src=/img/other-icons/nvidia-icon.svg height=24> Nvidia Jetson

## <img src="/img/app-icons/TeamViewer/icon-64.png"> TeamViewer
> Remote desktop server and client software.
> To run: Menu -> Internet -> TeamViewer
> To run in terminal: teamviewer
> If you get an error running it from command line follow the instructions it gives you. They're very simple to follow.

Fortunately, TeamViewer is very easy to install on your Nvidia Jetson in just two steps.
1. Install Pi-Apps - the best app installer for Nvidia Jetson.
2. Use Pi-Apps to install TeamViewer.
</div>
<div class="simple-install-content content">

## Compatibility
For the best chance of this working, we recommend using the latest version of [Nvidia Jetpack](https://developer.nvidia.com/embedded/jetpack-archive) for your specific Jetson (Jetson TX1, Jetson Nano, Jetson TX2, Jetson Xavier, or Jetson Orin).
TeamViewer will run on L4T Ubuntu ARM64.
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

## Install TeamViewer

Now that you have Pi-Apps installed, it is time to install TeamViewer.
First launch Pi-Apps from your start menu:
<img src="/img/start-menu.png">
Then click on the Internet category.
<img src="/img/category-selections/Internet.png">
Now scroll down to find TeamViewer in the list.
<img src="/img/app-icons/TeamViewer/app-selection.png">
Just click Install and Pi-Apps will install TeamViewer for you!
</div>
<div class="simple-install-content content">

Pi-Apps is a free and open source tool made by [Botspot and other contributors](/about/#contributors). Find out more at https://pi-apps.io
</div>
