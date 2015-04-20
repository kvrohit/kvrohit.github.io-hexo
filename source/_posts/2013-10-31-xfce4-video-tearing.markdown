---
layout    : post
title     : "Quick fix: XFCE4 video tearing"
date      : 2013-10-31
excerpt   : Xfwm 4.11 adds the sync to vblank feature; enable it to fix video tearing issues.
tags      :
- linux
- xfce
categories:
- blog
---
Xfwm 4.11 adds the sync to vblank feature; enable it to fix video tearing issues.

Open `Window Manager Tweaks > Compositor` tab and enable the 'Synchronize drawing to the vertical blank' setting.

![Xfwm vSync Settings](/img/xfwm-vsync-settings.png)
