---
description: How to get sciview going in stereo
---

# VR & AR

## Prerequisites

sciview works with all VR headsets that are supported by SteamVR, including:

* Oculus Rift S
* HTC Vive, HTC Vive Pro, HTC Vive Pro Eye
* Valve Index
* Windows Mixed Reality headsets \(such as the Samsung Odyssey\)

In addition, we have alpha-quality support for the Microsoft Hololens. Support for this AR headset will be extended in the future. For the moment and in the remainder of this article here, we concentrate on VR headsets.

In order to be able to use VR headsets for rendering in sciview, especially when rendering volumetric data, a relatively powerful computer is recommended. Our recommendation there would be to have at least 16-32 GB of RAM, and a GPU capable of fast VR rendering at high resolutions, such as a Geforce RTX 2080 or a AMD Radeon RX5700.

sciview relies on SteamVR/OpenVR for rendering to your VR headset. You can follow the [setup guide for the HTC Vive](https://support.steampowered.com/steamvr/HTC_Vive/) for setting it up, or use the one for your specific headset. Note that if you use a Windows Mixed Reality headset, you need to have [Windows Mixed Reality for SteamVR](https://store.steampowered.com/app/719950/Windows_Mixed_Reality_for_SteamVR/) installed in addition to SteamVR itself.

## Rendering to your VR headset in sciview

To activate rendering to an attached VR headset, choose `View`&gt; `Render to OpenVR HMD` in sciview's menu bar. If not already open, SteamVR will start and the current scene will appear in your VR headset.

