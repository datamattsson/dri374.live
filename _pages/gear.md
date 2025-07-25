---
layout: splash
title: GEAR FOR PINBALL AND ARCADE STREAMING
permalink: /gear
date: 2025-01-26T00:00
last_modified_at: 2025-03-15T00:00
header:
  video:
    id: AUOamxsqLo8
    provider: youtube
  og_image: /assets/images/gear/og_image.jpg
description: This is how to stream pinball and arcade games on Twitch.
feature_row1:
  - image_path: /assets/images/gear/dri374-16x9.png
    alt: "TWITCH.TV/DRI374"
    title: "DRI374"
    excerpt: "DRI374 is an eclectic pinball and arcade streamer that stream games, tournaments and cover events from time to time. Make sure to check out the VODs and highlights on [YouTube](https://www.youtube.com/@DRI374)."
    url: "https://twitch.tv/dri374"
    btn_label: 'Watch LIVE on Twitch <i class="fa-solid fa-arrow-up-right-from-square"></i>'
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/gear/la-16x9.png
    alt: "TWITCH.TV/LYNNSARCADE"
    title: "Lynn's Arcade"
    excerpt: "Lynn's Arcade is a Pinball Parlor and Can Slangery in Seaside, CA. They stream the Monterey Flipper Pinball and Monterey Flipper Ladies Pinball leagues along with staff shenanigans and big weekend tournaments."
    url: "https://twitch.tv/lynnsarcade"
    btn_label: 'Watch LIVE on Twitch <i class="fa-solid fa-arrow-up-right-from-square"></i>'
    btn_class: "btn--inverse"
feature_row3:
  - image_path: /assets/images/gear/the-rewind-16x9.png
    alt: "TWITCH.TV/THEREWINDARCADE"
    title: "The Rewind Arcade"
    excerpt: "The Rewind Arcade is a pinball and classic arcade game venue in Sebastopol, CA. They stream tournaments and events on Twitch."
    url: "https://twitch.tv/therewindarcade"
    btn_label: 'Watch LIVE on Twitch <i class="fa-solid fa-arrow-up-right-from-square"></i>'
    btn_class: "btn--inverse"
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

{% include feature_row id="intro" %}

This page contains the rough bill of materials for various streaming rig setups DRI374 is running and built for others.

- [Raccoon City Pinball](#raccoon-city-pinball) (the main home rig)
- [Raccoon City Arcade](#raccoon-city-arcade) (the candy cab rig)
- [The Pocket Rig](#the-pocket-rig) (tournament and event rig)
- [The Flying B-Cam](#the-flying-b-cam) (the unboxing setup)
- [Miscellaneous](#miscellaneous) (my favorite nick-nacks)
- [Lynn's Arcade](#lynns-arcade) in Seaside, CA
- [The Rewind Arcade](#the-rewind-arcade) in Sebastopol, CA

Make sure to check out the [Start Streaming Pinball!](https://youtu.be/AUOamxsqLo8) ([slides](https://bit.ly/gspf2024)) talk on YouTube and join us on Tilt Forums to discuss [Twitch/livestream setups](https://tiltforums.com/t/twitch-livestream-setups/107).

All the 8020 frames I've built stem from [this basic frame](https://docs.google.com/spreadsheets/d/1iUT8dXKl584KpI9j4cvNnXwCEF2QxplG75yA9rWUVCc/edit?gid=0#gid=0) by Karl DeAngelo. Just pay attention to if you need to roll your rig through door frames as his design does not roll under standard door frames with roller skate sized wheels. I shortened the vertical segments by 1/2". I have a ton of add-ons I might document in the future though.

As this page is updated, the [changelog](#changelog) lists the changes.

**FYI:** Most links below are Amazon affiliate links. No change in cost to you but a fraction of the margins goes to my Amazon store credit to continue this addiction.
{: .notice--danger}

# Raccoon City Pinball
The home pinball rig has evolved since early 2020 when I built a makeshift COVID rig to stream my newly acquired Stranger Things. Today, my home arcade is more of a studio than an arcade. The entire rig is one homogeneous unit only tethered by a power cord.

<figure class="align-right" style="width: 30%;">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/gear/rcp-2025-01-29.jpg" alt="" />
  <figcaption>The main home rig.</figcaption>
</figure>

* [Macbook Pro M3 Max](https://amzn.to/4hrpnpw) laptop.
* [Black Magic Design UltraStudio 4K Mini](https://amzn.to/4hxHI4e) capture card.
* [OREI UHD-401MV 4x1 HDMI Multi-Viewer](https://amzn.to/4hu6cLV) with [RigC](https://github.com/datamattsson/rigc).
* [StarTech Ethernet-to-Serial server](https://amzn.to/3Rbpavz)<sup>1</sup> for the Multi-Viewer (direct serial currently has [issues](https://discussions.apple.com/thread/255763367)).
* [StarTech USB-C hub with Ethernet](https://amzn.to/41VmMho)<sup>1</sup> for more ports.
* [Elgato Stream Deck MK.2](https://amzn.to/3WBBTeh).
* [Elgato Stream Deck Pedal](https://amzn.to/3WBnoHb) for fast switching.
* [Belkin USB-C to HDMI](https://amzn.to/4ixpTmD) for an additional HDMI port.
* [Lilliput A11](https://amzn.to/4aDkbwz) for chat and stream monitoring.
* [Atomos Ninja 5.2"](https://amzn.to/40MYM0y) 4K HDMI recording monitor.
* 2 x VILTROX L132T (discontinued [L116T](https://amzn.to/3WBWPBL) sub) LED lights.
* [Audio-Technica AT2040](https://amzn.to/42vJu1v) player mic with a [Behringer VU1](https://amzn.to/3QDQ5QB).
* [Audio-Technica AE3000](https://amzn.to/42oSuWl) backbox mic on a dbx 166xs (discontinued, sub [dbx 266xs](https://amzn.to/4jvoYEr)) channel.
* [Shure PGA52-XLR](https://amzn.to/3E7xd9E) cabinet mic on the other dbx 166xs (discontinued, sub [dbx 266xs](https://amzn.to/4jvoYEr)) channel.
* [Mackie 1202VLZ4](https://amzn.to/3CdY6It) mixer.
* [LUMIX GH5M2](https://amzn.to/42pZZfJ) playfield camera with a [LUMIX G Vario 12-35mm](https://amzn.to/4ktnxH4) lens.
* [LUMIX GH5M2](https://amzn.to/42pZZfJ) player camera with a [Laowa 6mm f/2 Zero-D](https://www.venuslens.net/product/laowa-6mm-f-2-zero-d-mft/) lens.
* LUMIX GX85 (discontinued, [G85](https://amzn.to/40vciVw) sub) score camera with LUMIX G Vario 12-60mm lens.
* [LUMIX GH5M2](https://amzn.to/42pZZfJ) B camera with various lenses.
* [Accsoon CineView HE](https://amzn.to/3CxGXcA) for local program output to the arcade TV.
* [Sony MDR-EX15LP](https://amzn.to/3E6hHdW) ear buds.

The Atomos recorder uses the passthrough of the capture card and records the multi-viewer output in 2160p60 with the mixer output. Highlights destined for YouTube are rendered through a template in DaVinci Resolve for that souped up 4K rendering.

<small><sup>1</sup> = The StarTech hub and ethernet-to-serial server is sandwiched together and used in the pocket and event transform as well.</small>

# Raccoon City Arcade
<figure class="align-right" style="width: 25%;">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/gear/rca-2025-01-25.jpg" alt="" />
  <figcaption>The candy rig.</figcaption>
</figure>

The candy cab rig is a half-height regular pinball rig. It uses the same laptop, player camera, player microphone and Stream Decks as the pinball rig.

* [OREI UHD-401MV 4x1 HDMI Multi-Viewer](https://amzn.to/4hu6cLV) with [RigC](https://github.com/datamattsson/rigc).
* [Elgato 4K X](https://www.elgato.com/us/en/p/game-capture-4k-x) capture card.
* [Yamaha AG03MK2](https://amzn.to/3PT5rAm) mixer.
* [Mackie MP-240](https://amzn.to/3PRyCn7) IEMs.
* [TC-Helicon VoiceTone T1](https://amzn.to/40vcrIy) stomp box.
* 2 x [VILTROX L116T LED](https://amzn.to/3WBWPBL) lights.
* [Lilliput A7s](https://amzn.to/40pvT9u) for chat and stream monitoring.
* [NAC Splitfire](https://birdlandarcade.com/products/splitfire?variant=36978386403478) + [OSSC Classic](https://videogameperfection.com/products/open-source-scan-converter/) for arcade game capturing.

This rig seldom see content but there's a whole lot of ambition with several projects in the pipeline.

# The Pocket Rig

The notorious "pocket rig" has seen the most evolution as I've always wanted to be mobile. The current incarnation has three different configurations and I'll try describe them separately.

### The Event Transform

This is the configuration that captured that notorious [Metallica game at Pinball Expo '24](https://youtu.be/4yKe8FUl7aE?si=flF8HHLuf5HjrRCF). It has everything needed mounted to the rig that allow about four hours of game capture/streaming.

The only components shared with the home rig is the laptop and the Stream Deck. The Atomos recorder might go into this build for a higher quality event capture.

<figure class="align-right" style="width: 33%">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/gear/pocket-2025-01-29.jpg" alt="" />
  <figcaption>The Pocket Rig. Photo by <a href="https://www.instagram.com/braddukeart/">Brad Duke</a>.</figcaption>
</figure>
* [OREI UHD-401MV 4x1 HDMI Multi-Viewer](https://amzn.to/4hu6cLV) with [RigC](https://github.com/datamattsson/rigc).
* [AVerMedia Live Gamer Ultra 2.1](https://amzn.to/40Z4EEp) capture card.
* 2 x [RØDE VideoMic GO II](https://amzn.to/40OxW8A).
* [Belkin Connect USB-CTM to 4-Port USB-C Hub](https://amzn.to/3ElUcgZ) for more ports.
* VILTROX L132T (discontinued [L116T](https://amzn.to/3WBWPBL) sub) LED light for the playfield.
* [Logitech Litra Glow](https://amzn.to/4giYP8W) player light.
* [LUMIX GH5S](https://amzn.to/4kwCWWc) with a [LUMIX G FISHEYE 8mm f/3.5](https://amzn.to/4mtRE20) lens.
* [Panasonic V785K](https://amzn.to/3ElUCE5)<sup>1</sup> playfield camera.
* [Panasonic V785K](https://amzn.to/3ElUCE5)<sup>1</sup> score camera.
* 3 x [AMEGAT/Alfox/Ravpower 140W 27600mAh](https://amzn.to/44WWflj) power banks for all gear except laptop.
* 2 x [UGREEN 145W 25000mAh](https://amzn.to/4hu6pib) for the laptop.

All the gear needed for the event rig fits into two [Pelican 1510](https://amzn.to/4h9MtkU) carry-on sized cases.

<small><sup>1</sup> = Both the Panasonic V785K and V770K are a bit finicky to set the correct white balance on. Put [this card](https://amzn.to/43S6g4r) on the playfield glass, zoom in, and use that to program the white balance for your venue. It will be saved between power cycles.</small>

### The Single Day Tournament Transform
<figure class="align-right" style="width: 35%">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/gear/tourney-rig-2025-01-29.jpg" alt="" />
  <figcaption>The tournament rig.</figcaption>
</figure>

This adds another [Pelican 1510](https://amzn.to/4h9MtkU) case of gear to the event transform and suitable for single day tournaments. This kit does not provide any telestrating capability and only two hosts for the broadcast. The Atomos recorder is used for tournaments to record the program as well as pushing the program to venue monitors with the passthrough to a HDMI splitter.

An additional harness is tacked onto the rig and make the mics go analog and adds an additional mic for the cabinet.

* [TP-Link AXE75](https://amzn.to/40zFwm8) mesh satellite (scrapped, testing a new brand TBA).
* [KiloView N60](https://amzn.to/4jyquFN) NDI encoder.
* StarTech NETRS2321P (discontinued, [sub](https://amzn.to/3Rbpavz)) Serial-to-Ethernet for RigC.
* [Maker hart Just Mic 4 mini](https://amzn.to/43qsDft) mixer.
* [RØDE VideoMicro II](https://amzn.to/4jLHMQ7) for the cabinet.

The broadcast station is scarce in this setup and has the following components:

* [TP-Link AXE75](https://amzn.to/40zFwm8) mesh router (scrapped, testing a new brand TBA).
* [CalDigit Thunderbolt 3 Mini Dock](https://amzn.to/3E8RUlr) for more ports.
* [Lilliput A7s](https://amzn.to/40pvT9u) for chat and stream monitoring.
* [Black Magic Design Monitor 3G](https://amzn.to/4htAwGs) for program recording.
* [ASUS ProArt Display 14"](https://amzn.to/3CsfKbp) monitor for broadcasters.
* [Insta360 Link](https://amzn.to/40yCNJp) broadcast talent camera.
* 2 x [Koss Porta Pro](https://amzn.to/3Eduw6r) headsets.
* [Focusrite Vocaster Two](https://amzn.to/4hxzFEA) for headsets.

Technically, the single day rig can be flown with if there's two people traveling as the gear needs to be in the cabin and the rig in the hold.

### The Multi Day Tournament Transform
<figure class="align-right" style="width: 36%">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/gear/tourney-broadcast-2025-01-29.jpg" alt="" /> 
  <figcaption>The multi day broadcast station.</figcaption>
</figure>

The multi day tournament transform uses all the gear from the single day transform except the 14" portable monitor.

* [OREI 1x4 HDMI splitter](https://amzn.to/3CsGybr) for program outputs.
* [Dell 27" FullHD](https://amzn.to/40OSMoc) monitor.
* [Magewell UltraEncode HDMI Plus](https://www.magewell.com/products/ultra-encode-hdmi-plus) for telestrating output over NDI.
* [Surface Go 3](https://amzn.to/4jx3A1p) with [WebRTC-Telestrator](https://github.com/BlankSourceCode/WebRTC-Telestrator).
* An additional [Koss Porta Pro](https://amzn.to/3Eduw6r) headset.
* [Sennheiser EM 100 G4](https://amzn.to/40Po9yU) receiver.
* [Sennheiser IEM G4](https://amzn.to/3CsfPfd) transmitter.
* 2 x [VILTROX L116T](https://amzn.to/3WBWPBL) talent lights.

The additional headset is completely wireless for both monitoring and voice and allows the broadcaster to roam freely and commentate and manage the stream from anywhere in the venue.

### The Flying B-Cam
<figure class="align-right" style="width: 36%">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/gear/bcam-2025-03-15.jpg" alt="" /> 
  <figcaption>The b-cam.</figcaption>
</figure>

During unboxing and other tech type streams I have a "flying b-cam", it's not really a b-cam for all intents and purposes but it's secondary purpose to what my productions are all about, gameplay. So, I call it a b-cam.

* [LUMIX GH5M2](https://amzn.to/42pZZfJ) with a [LUMIX G Vario 12-60mm](https://amzn.to/3RaPlCz) lens.
* [NICEYRIG cage](https://amzn.to/4ivJVOo) for the house, various SmallRig handles/mounts.
* [Logitech Litra Glow](https://amzn.to/4giYP8W) light.
* [DJI Mic 2](https://amzn.to/3Rgksws) wireless mics, usually with [Shure MVL](https://amzn.to/3XVJgO6) lavaliers.
* [Accsoon CineView Master 4K](https://amzn.to/43S6R6b) for 2160p60 or 1080p60 HDMI transmission.
* [Blackmagic Design UltraStudio Recorder 3G](https://amzn.to/41utjj1)<sup>1</sup> for unboxing streams at Lynn's Arcade, otherwise it's plugged into the multi-viewer.
* [SmallRig NP-F970 battery](https://amzn.to/3Rabukm) powers camera, light and transmitter for about four hours.
* [Manfrotto Tripod](https://amzn.to/41uvWkT) for stationary shots.

All b-cam gear fit into yet another [Pelican 1510](https://amzn.to/4h9MtkU) carry-on sized case.

<small><sup>1</sup> = Since the CineView Master 4K only does 12Mbit/s max I haven't felt the need to get a 2160p60 standalone capture card for it just yet and mostly run it in 1080p60 on mobile gigs.</small>

# Miscellaneous

I've been through some gear over the years in terms of mounts, stands and other loose items to make life easier. This is a non-exhaustive list of favorites. 

- SmallRig Magic Arms. Comes in two sizes, [9.8"](https://amzn.to/3WzMO80) and [5.5"](https://amzn.to/3Cg30Vl)
- [CAMVATE crab clamp](https://amzn.to/3Eh127O). Nips perfectly into the 1515 extrusions and the rubber won't slip like with other brands.
- [UGREEN USB-PD plug 160W](https://amzn.to/4hckWiK)
- [Alfox USB-PD brick 200W](https://amzn.to/4aAvEwS)
- [Manfrotto counterfeit quick release](https://amzn.to/40OUO7E). All my cameras have these. Although, I've started to flirt with the [HawkLock](https://amzn.to/40waxY5).
- [ABS plastic](https://amzn.to/3CDUmzQ) to DIY hoods and barn doors for lights to prevent reflections.
- The [Velcro](https://amzn.to/3WEy2NA) I use for for the hoods and barn doors.
- The ["Velcro" rolls](https://amzn.to/3EbJl9H) I use to build wire harnesses.
- A newer version of the [laptop stand](https://amzn.to/40RhmVq) I use.
- [Schoche magnet mounts](https://amzn.to/40QqM3w). The laptop stand is peppered with these. Useful for small things, like USB hubs and capture cards.
- [Desk and wall rack mount frame](https://amzn.to/4gmBZx7) for up to 6U. Mounts perfectly onto a 1515 profile, flat or vertical.
- Flashner [CamCaddie cold shoe rails](https://amzn.to/4gmtMsW). Great for mounting an Accsoon triplet on.
- Don't want to build a 8020 frame? Get a [C-stand](https://amzn.to/3EfqHxB), with [wheels](https://amzn.to/3PSDSXL) and a [case](https://amzn.to/4jC7uWT). It holds a ton of gear.
- Monoprice makes my favorite cables. [Ultra slim HDMI](https://amzn.to/3WDB4kV) (good for 4K60 up to 8') and [Ethernet](https://amzn.to/3Cun2v8) (10GigE up to 30') cables.
- Monoprice also makes [active HDMI](https://amzn.to/4gdnmMR) (up to 15' and 4K60) cables.
- Faracent makes excellent [USB-PD extension cords](https://amzn.to/3ChLEYb) (up to 10').
- Blind Spot makes very professional [USB-PD to DC barrel](https://amzn.to/40xWJfH) cables but [many cheaper](https://amzn.to/3Wzgand) and [more practical](https://amzn.to/40QPmRL) cables exist, work and [sometimes more flexible](https://amzn.to/4hqMr7Y) on the output (check your power bank and device).
- When using a USB-C port to yield another HDMI port, use high quality adapters. Brands certified with Apple works best. Like [this Belkin](https://amzn.to/4ixpTmD). Off brands may glitch and that glitch will cause OBS to crash (on Mac).
* [Anker 4-Port USB 3.0](https://amzn.to/3CkSs7j) works for more USB-A ports and [Belkin 4-Port USB-C Hub](https://amzn.to/3ElUcgZ) for more USB-C ports.

The power banks I buy at the moment, [AMEGAT 140W 27600mAh](https://amzn.to/44WWflj), provide two USB-PD ports and one USB-A. These are OEMs and I don't know the source. Ravpower had them first but then a ton of other brands started to carry them. The display with the individual draw per port is brilliant as it's easy to balance and you get immediate feedback if there's draw from the connected device.

**Pro-Tip:** The brand Anker seems to have very compelling power banks, warts, bricks and plugs. *READ THE FINE PRINT:* I've not come across a single product that does 12V 3A which is the most common voltage USB-PD is used for.
{: .notice--danger}


{% include feature_row id="feature_row1" type="left" %}

# Lynn's Arcade

The rig at Lynn's I originally built for myself but the arcade decided to buy it. There's been a few upgrades over the years and this list is the current known list of equipment.

<figure class="align-right" style="width: 33%">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/gear/lynns-2025-01-29.jpg" alt="" />
  <figcaption>The rig at Lynn's Arcade.</figcaption>
</figure>
* 3 x [Accsoon CineView HE](https://amzn.to/3CxGXcA) transmitters
* Panasonic V770K (discontinued, sub [V785K](https://amzn.to/3ElUCE5)) playfield camera
* Panasonic V770K (discontinued, sub [V785K](https://amzn.to/3ElUCE5)) score camera
* LUMIX GX85 (discontinued, sub [G85](https://amzn.to/40vciVw)) player camera with a [Rokinon fisheye](https://amzn.to/3CBZZhY) lens
* 2 x [Audio-Technica AT897](https://amzn.to/3POWzeS) shotgun mics
* [Yamaha MG06](https://amzn.to/4aAfUKz) mixer
* VILTROX L132T (discontinued, sub [L116T](https://amzn.to/3WBWPBL)) playfield light
* [VILTROX L116T](https://amzn.to/3WBWPBL) player light

Broadcaster station. 

* [HP desktop PC with a GeForce RTX 3080](https://amzn.to/4ax9mME)
* 3 x [Accsoon CineView HE](https://amzn.to/3CxGXcA) receivers
* Dual displays for monitoring (unknown)
* [Magewell Quad HDMI](https://amzn.to/3WyM7Mv) capture card
* [Rodecaster Duo 2](https://amzn.to/40yEbM9) mixer
* 2 x [Audio-Technica BPHS1](https://amzn.to/3Wzt4l6) headsets
* LUMIX GX85 (discontinued, sub [G85](https://amzn.to/40vciVw)) talent camera with a [Laowa 6mm f/2 Zero-D](https://www.venuslens.net/product/laowa-6mm-f-2-zero-d-mft/) lens

The rig at Lynn's Arcade can be "rented" at the arcade if you bring a laptop with a USB4 or TB3 port. Affectionately called the Rent-A-Rig (or RAR). Instructions how to use the RAR will be made available soon.

{% include feature_row id="feature_row2" type="right" %}

# The Rewind Arcade

The Rewind Arcade picked up my previous generation of gear that was PC based using dedicated HDMI transmitters.

<figure class="align-right" style="width: 40%">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/gear/rewind-case-2025-01-29.jpg" alt="" />
  <figcaption>The rig built for The Rewind Arcade.</figcaption>
</figure>
* 3 x Accsoon CineEye 2S Pro (discontinued, sub [CineView HE](https://amzn.to/3CxGXcA)) transmitters
* GoPro Hero 11 (discontinued, sub [13 w/ MediaMod](https://amzn.to/42oBVtE)) player camera
* [Panasonic V785K](https://amzn.to/3ElUCE5) score camera
* Sony CX405 (trash, sub [V785K](https://amzn.to/3ElUCE5)) score camera
* 2 x RØDE VideoMic GO (discontinued, sub [VideoMicro II](https://amzn.to/4jLHMQ7))
* 2 x [VILTROX L116T LED](https://amzn.to/3WBWPBL) lights
* 5 x 30,000mAh RAVPower (discontinued, sub [Alfox/Ravpower/AMEGAT 140W 27600mAh](https://amzn.to/44WWflj) or [HenHot 30,000mAh](https://amzn.to/4m54Byo)) banks

The broadcast station: 

* [Razer Blade 15 2020](https://amzn.to/4giZjvM)
* [Magewell Quad HDMI](https://amzn.to/3WyM7Mv) in a [SonnetTech](https://amzn.to/4hssBsU) enclosure
* 3 x CineEye 2S Pro (discontinued, sub [CineView HE](https://amzn.to/3CxGXcA)) receivers
* Canon VIXIA HF R800 (discontinued, sub anything) broadcast talent camera
* [Logitech Litra Glow](https://amzn.to/4giYP8W) player light
* Rodecaster Pro (the old model, sub with [Rodecaster Duo 2](https://amzn.to/40yEbM9))
* 2 x [Audio-Technica BPHS1](https://amzn.to/3Wzt4l6) headsets

Two rifle cases ([Harbor Freight models](https://www.harborfreight.com/9800-weatherproof-protective-rifle-case-long-black-64520.html)) to hold all the gear.

{% include feature_row id="feature_row3" type="left" %}

# Changelog

* 2025-07-21: Updated power bank links.
* 2025-05-22: New pocket mixer, decommissioned [Zoom AMS-44](https://amzn.to/4aASioN), new player camera, decommissioned [LUMIX G85](https://amzn.to/40vciVw).
* 2025-03-15: New USB hub. Clarified white balance on the V785/V770's. B-cam rig.
* 2025-03-02: Replaced the dbx286s (gain of death) with a Behringer VU1. Clarified using RØDE mics with the Zoom AMS.
* 2025-01-29: Added some pictures.
* 2025-01-28: Cables (under Misc.) and typos and such.
* 2025-01-27: Added Miscellaneous section and dbx links. Clarified AMZN links. Link to slides.
* 2025-01-26: Initial hack.
