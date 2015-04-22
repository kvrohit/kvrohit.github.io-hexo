---
layout    : post
title     : XFCE tricks
date      : 2013-10-24
excerpt   : Binding hardware volume control to mixer
tags      :
- linux
- xfce
categories:
- tutorial
---
Binding hardware volume control to mixer

Go to `Settings > Keyboard > Shortcuts` and add the following:

```bash
amixer set Master 5%+
amixer set Master 5%-
amixer set Master toggle
```

Source: [http://schman.at/shortcuts-mit-xfce-setzen](http://schman.at/shortcuts-mit-xfce-setzen)
