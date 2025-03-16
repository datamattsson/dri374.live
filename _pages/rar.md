---
layout: single
classes: wide
title: RENT-A-RIG AT LYNN'S ARCADE
permalink: /rar
date: 2025-03-15T00:00
last_modified_at: 2025-03-15T00:00
sidebar:
- image: /assets/images/rar/rar.png
  image_alt: Rent-A-Rig by Lynn's Arcade
  text: '<i class="fa-solid fa-laptop"></i> Bring your laptop.<br/><i class="fa-solid fa-video"></i> Stream Pinball LIVE!<br/><i class="fa-solid fa-people-group"></i> Build a community.'
header:
  og_image: /assets/images/rar/og_image.jpg
description: How to use the Rent-A-Rig at Lynn's Arcade.
---

<style type="text/css">
ul li, ol li {
    margin-bottom: 0;
}
figure {
    margin-left: 10px;
    margin-top: 0;
    margin-bottom: 0;
}
figure img {
    border-width: 2px;
    border-style: solid;
    color: #FF69B4;
    margin-top: 0;
    margin-bottom: 0;
}
</style>

The streaming rig at Lynn's Arcade can be rented by streamers when it's not being used by the arcade. The idea is that a streamer only need to bring their own laptop to gain access to a video feed available on the network that can be consumed by the streamer's OBS instance.

The Rent-A-Rig concept is currently under review and may change at any time without notice.<br />Contact [Lynn's Arcade](https://www.lynnsarcade.com) for any Rent-A-Rig rental inquiries. 
{: .notice--danger}

Table of contents: 

- [Requirements](#requirements)
- [NDI and DistroAV](#ndi-and-distroav)
- [OBS Scene Setup](#obs-scene-setup)
- [Rig Maneuvering](#rig-maneuvering)
- [Have Fun!](#have-fun)

## Requirements

The streamer needs to bring their own laptop. The laptop itself needs a Thunderbolt or USB4 USB-C port. The streamer plugs into a dock that provide a physical network port that use automatic configuration, i.e DHCP.

Tip: It's not recommended to be connected to the arcade's WiFi at the same time.
{: .notice--info}

**Optionally:** The dock also provide a HDMI output where the OBS program can be displayed on the TVs above the laptop.

The video with embedded audio from the rig is delivered over a protocol called [NDI](https://ndi.video/tech/) (Network Device Interface). 

Software needs to be installed on the laptop (Mac, Windows or Linux) along with a plugin for OBS. Let's go through those steps first.

## NDI and DistroAV

The company behind NDI provide packages and installers for the various components required to consume and produce NDI video feeds. DistroAV is the name of the OBS plugin (formerly called OBS-NDI).

The DistroAV team maintains a [wiki with links](https://github.com/DistroAV/DistroAV/wiki/1.-Installation) to all the installers for the various operating systems. For convenience, here are the two most commonly needed.

- Windows: [http://ndi.link/NDIRedistV6](http://ndi.link/NDIRedistV6)
- macOS: [http://ndi.link/NDIRedistV6Apple](http://ndi.link/NDIRedistV6Apple)

Once installed, make sure OBS is closed and download the [latest DistroAV release](https://github.com/DistroAV/DistroAV/releases/tag/6.0.0) (download the suitable installer from the **Assets** at the bottom of the page).

## OBS Scene Setup

At this point all the software should be installed, the laptop plugged into the dock and the staff at Lynn's should fire up the RAR instance of OBS on their streaming PC.

To better illustrate what is being consumed on the streamer's laptop, this is what the feed looks like. Each quadrant in the feed is 1920x1080 pixels.

<figure class="align-center" style="width: 100%;">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/rar/rar-pc.jpg" alt="" />
  <figcaption>Lynn's Arcade streaming PC broadcasting the RAR 2160p60 video feed on the network</figcaption>
</figure>

The following steps assumes OBS on the streamer's laptop is using a 1080p60 canvas.

- Create a new scene. Let's call it **playfield**.
- In the new scene, add an **NDI® Source** ➔ **Create new**, name it **RAR**.
- In the dialog, configure it according to this screenshot:

<figure class="align-center" style="width: 100%;">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/rar/ndi-dialog.png" alt="" />
  <figcaption>The NDI® Source dialog</figcaption>
</figure>

- Position the playfield to fill the scene. 
- Repeat the steps above for each quadrant of the video feed, but instead of **Create new**, select **Add existing** NDI source and pick **RAR**.

**Pro-tip:** Adding the same NDI source multiple times as a separate scene source will create a strain on the network and the video will stutter, be out of sync and create fun sound effects we don't want.
{: .notice--danger}

There should now be three scenes (optional RAR logo), one for each camera. In the main overlay where there normally are the streamer's home cameras, the scenes just created should be add as sources in the scene.

Syncing video with audio in a live setting has proven to be the single most difficult thing to accomplish in the history of Twitch streaming.

In the OBS audio mixer, bring up the **Advanced Audio Properties** dialog by clicking the three dots on the **RAR** audio channel. 

<figure class="align-center" style="width: 100%;">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/rar/audio-delay.png" alt="" />
  <figcaption>The Advanced Audio Properties dialog</figcaption>
</figure>

When using OBS on a MacBook Pro M3, setting the offset to **-100ms** has turned out to be OK (this can NOT be adjusted further on the streaming PC providing the feed).

In theory, that **Start Streaming** button is ready.

## Rig Maneuvering

Moving the rig around in the arcade is the responsibility of the streamer once it's outside of the behind the bar area. Staff may help if you ask politely.

Here are a few pointers.

- When wheeling the rig around, hold the rig with both hands as far up as you can. This will make it easier to parry if a wheel comes to a screeching halt or gets locked in a crack.
- Moving the rig sideways is much safer as it's less prone to fall over sideways.
- The only camera that is allowed to be physically moved out of position with its magic arm is the score camera.
- The zoom button of the playfield camera is located on the top far back, the same place as on the score camera.
- Position the mics as needed and check the sound levels with the headphones. Only adjust each channel's volume knob, nothing else. Put the volume knobs where marked on the mixer if uncertain.

## Have Fun!

We don't need a real purpose to stream pinball. There literally is [no point](https://youtu.be/vcC032eqxvg?si=F9RjgauNbk6x4Msj) other than for fun. Not everyone understand the very concept of enjoyment.

If you think the RAR is cool, spread the word and tell a friend! Get [the swag](https://swag.dri374.live/products/65724794-rent-a-rig-t-shirt) and put the [digital sticker]({{ site.url }}{{ site.baseurl }}/assets/images/rar/rar-logo.png) in your overlay.
