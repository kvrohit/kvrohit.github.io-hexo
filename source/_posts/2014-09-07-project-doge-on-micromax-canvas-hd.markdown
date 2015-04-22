---
layout    : post
title     : "Project Doge on Micromax Canvas HD"
date      : 2014-09-07
excerpt   : Install Android Kitkat on Micromax Canvas HD
author    : Rahul Viswanath
tags      :
- android
- custom rom
- project doge
- kitkat
- micromax canvas hd
categories:
- tutorial
---
Install Android Kitkat on Micromax Canvas HD (A116)

For those of you, who are willing to flash their ROM and install Android Kitkat, can follow these steps.
This procedure may be compatible with all Micromax devices having the corresponding configuration:

1. MediaTek 6589/6589T Chipset
2. 1 GB RAM

***WARNING! Flash at your own Risk!***

Prerequisites:

1. Rooted phone
2. Micromax drivers installed on your system

Before you start, check out [Project Doge at xda-developers forum](http://forum.xda-developers.com/showthread.php?t=2663763) to an idea about this ROM

<!-- more -->

### Step 1: Downloads

Firstly, you need to download a bunch of zip and config files. Here's the list of things that you will need

1. [Project_Doge](http://www.mediafire.com/download/v9z7g8cdiqdxoxy/ProjectDoge_Final.zip)
2. [TeamWin Recovery Project (TWRP)](http://forum.xda-developers.com/attachment.php?attachmentid=2919302&d=1409485629)
3. [SP Flash Tool](http://www.mediafire.com/download/aix6jxmcbxmmc2b/SP+Flash+Tool+3.1352.01+%285.1352.01%29.rar.html)
4. [MT6589\_Android\_scatter_emmc.txt](https://docs.google.com/file/d/0B535lPY6topPd2I1N0NWQklDa0U/edit)
5. [Project_Doge Update 1](https://docs.google.com/file/d/0BwbIKpGKHSwHaUVoSzgtUHVKbEU/edit?pli=1)
6. [Project_Doge Update 2](https://docs.google.com/file/d/0BwbIKpGKHSwHdk9UcFhtOEFELVE/edit?pli=1)

Few of these downloads can be slow. Use a download manager for better results.
Unzip the following to have easier access to the files -
TWRP, SP Flash Tool, and Project_Doge

### Step 2: TWRP install

Next, you need to install TWRP. Follow these steps

1. Open flash_tools.exe as Administrator. You will find this in the unzipped SP Flash tool folder.
2. Select Options -> Option... -> Connection -> USB
Enable options - "High speed" under USB Speed and "with Battery" under Battery.
3. Click on "Scatter-loading" button and point to file : MT6589\_Android\_scatter_emmc.txt.
4. You will then see a list of items. Make sure that everything except RECOVERY is unchecked.
5. Click on location corresponding to RECOVERY and point to file recovery.img. You will find this in the
unzipped TWRP folder.
6. Now, click on the Download button which you'll find above the list. Switch off your phone and connect it to
your system. Once the download process is complete, you will see a pop up.

### Step 3: Recovery Image

Since you're doing this at your own risk, create a backup of your Stock ROM. Follow these steps

1. Power off your phone, if it isn't already. Hold "Volume Up key + Power key" until the phone boots to
TeamWin recovery screen
2. Click on "Backup". In the next screen, make sure the following items are selected
System, Data and Boot
3. You can save the recovery image either on your internal SD or the external SD depending on how much
disk space you have. Once all your options are selected, swipe to backup.
4. Once the backup is complete, reboot your device and then connect it to your system as "USB Storage".

### Step 4: Install Project_Doge

Now, lets move on to the next stage.

1. Now that you're connected to your system as "USB Storage", copy Project_Doge and the 2 updates into your
internal/external SD card. Power off the phone.
2. Hold "Volume Up key + Power key" to open TWRP. Select "Wipe" option - wipe "cache", "dalvik cache" and then
do a "factory reset".
3. Go back to the main menu and select "Install". Then select the main Project_doge_final.zip, then flash ROM.
Wait for the process to complete and when asked for any setup, follow the instructions.
4. Go back to the main menu and select "Install". Repeat the above process for the 2 update files as well..
Once all this is done, reboot your phone. Select power down, if you have the option, else switch off
your device once the reboot is complete.

### Step 5: Bootloader

One last step to go

1. Once again, open flash_tools.exe as Administrator.
2. Select Options -> Option... -> Connection -> USB
Enable options - "High speed" under USB Speed and "with Battery" under Battery.
3. Click on "Scatter-loading" button and point to file : MT6589\_Android\_scatter_emmc.txt.
4. You will then see a list of items. Make sure that everything except BOOTIMG is unchecked.
5. Click on location corresponding to BOOTIMG and point to file boot.img. You will find this in the
unzipped Project\_Doge\_final folder.
6. Now, click on the Download button which you'll find above the list. Switch off your phone and connect it to
your system. Once the download process is complete, you will see a pop up.

Power on your phone and follow the initial setup. This ROM consists of all the best features from Timescape UI, HTC Sense,
Sony Xperia and Stock Android. Take some time to fiddle around and setup your device the way you want.
