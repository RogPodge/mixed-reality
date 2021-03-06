---
title: HP Reverb G2 FAQs
description: Commonly asked questions about using HP Reverb G2 headset
ms.author: v-hferrone
ms.date: 09/15/2020
ms.topic: article
keywords: Windows Mixed Reality, Mixed Reality, Virtual Reality, VR, MR, Troubleshoot, Errors, Help, Support, Performance
appliesto:
    - Windows 10
---

# HP Reverb G2 Frequently Asked Questions

## Is there a specific order I should follow to connect my headset cables to a PC

HP Recommends:

- Connect the 6-meter cable to the headset first before connecting to the PC or power supply.
- Leave the 6-meter cable connected to the headset after initial installation.
- When the headset is not in use, disconnect the power adapter from the 6-meter cable.

## What should I do to get a crisper image

There are a few things you can try if you feel that your display looks a little blurry:

- Make sure that your headset is on your head correctly so that your eyes are centered with regards to the lenses.
- Try to adjust the IPD (interpupillary distance). Note that Reverb G2 uses a hardware IPD. To change it, look for IPD adjustment on your headset.
- If you need glasses or contacts, they are still required.
- Check your lenses if they need to be cleaned (microfiber cloth only – no fluids).
- Due to the advanced design of the headset there may be some minor image ghosting in the first few minutes when starting the device while cold until the LCDs have the opportunity to warm up.

## I am getting a 7-14 “Something Went Wrong” error when I plug in my headset

The 7-14 Something Went Wrong code means that some of the required USB2 components weren’t found.  Due to the extra-long cable of the HP Reverb G2, some of the tolerances for the USB signals are tighter.  This means that one port on your computer may work more reliably than another.

If you are seeing a 7-14 “something went wrong” error, please try the following steps:

- Make sure that you have the most recent drivers installed for your headset and your USB controller.
- Make sure you are using a Microsoft USB driver. There should be a “Microsoft” in the name of the "eXtensible Host Controller" device.
- Try plugging the cable into a different USB-3.0 port on your computer. (Try USB Type-C and Type-A ports)
- Use the included USB C to A adapter included to try different ports.
- Try plugging the headset in through a USB Hub to your computer.

> [!NOTE]
> HP recommends using only USB controllers built into the motherboard with Reverb G2
> devices.
> If you are unable to connect your device, please contact [HP Support](https://support.hp.com/us-en)

## I am getting a 13-14 “Something Went Wrong” error when my PC resumes from hibernate (S4)

Sometimes during the resume process, the video card cannot establish a connection, so unplugging the USB Type C from your PC and plugging it back in may help to establish a connection.

## The Mixed Reality Portal says “Can't run mixed reality on this headset” but this worked fine with my previous WMR headset

This may happen because your HP Reverb G2 requires a more powerful PC to ensure the best experience. For more information, please review the minimum [PC requirements](windows-mixed-reality-minimum-pc-hardware-compatibility-guidelines.md)

## It looks like my left display is stretched, and the right display is off-centered and half black

This can happen when your headset is not running at the native resolution. Due to the nature of the high-resolution displays in the HP Reverb G2 HMD, not all systems will be able to render the native resolution. There is a fix coming in a future Windows Update that will address the rendering issue when the headset is not at the native resolution.

There are a few reasons why your system is not able to render at the native resolution:

- The DisplayPort on the system might not be 1.3 compatible, or it might not support all 4 lanes.
- If you are using an adapter, it might not support be HBR3 compatible, or it might not support all 4 lanes.
- If your system has a hybrid GPU, that might be limiting the bandwidth available to the DisplayPort.

## Why are my HP Motion Controller models not showing up correctly in a game

While most games do not display the controllers or use the models installed by the driver, some games use their own versions of the controller models, either to customize them or to display contextual help for the available inputs. Usually, this does not block any features of the games but might lead to confusion or even visual artifacts. This can only be fixed with an update of the game itself.

## My SteamVR games don't appear to work correctly with my HP Motion controllers

While developers are working to update their games for HP Motion Controller compatibility, we have provided custom controller bindings for many of the most popular games on Steam. With "Windows Mixed Reality for SteamVR" fully updated to version 1.2.444, these bindings should be picked up automatically when your game is running. However, if your game does not seem to register your actions at this time, you can manually search for custom binding profiles using the SteamVR Settings menu.
To do this

- Open the SteamVR menu by pressing the right motion controller's menu button
- Select the "Settings" icon in the bottom-right corner of the SteamVR menu
- Select the "Controllers" tab
- Select the "Manage Controller Bindings" option

From here you can change your active controller binding to "Custom" which will open up the option to try community-shared game bindings.
If no custom game bindings have been shared for this game yet (or if you are not fully satisfied with the ones you've tried), you can also create your own custom game bindings, and even help the rest of the community by sharing them after a few game sessions.