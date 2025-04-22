# Awesome Ndi [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Network Device Interface is a royalty-free software standard developed by NewTek to enable video-compatible products to communicate, deliver, and receive broadcast-quality video in a high-quality, low-latency manner that is frame-accurate and suitable for switching in a live production environment.

> This is a curated list of tools related to NDI.

<img src="./media/apple.svg" height="14"> = macOS builds
<br /><img src="./media/windows.svg" height="14"> = Windows builds
<br /><img src="./media/linux.svg" height="14"> = Linux Builds
<br />✉️ = Requires e-mail for download

## Contents

- [🔓 SDK Libraries](#-sdk-libraries)
- [🛠️ Converters & Tools](#-converters--tools)
- [👓 Software Vision Mixers](#-software-vision-mixers)
- [🔴 Playback & Recording](#-playback--recording)
- [🖌️ Graphics](#-graphics)
- [📡 Contribution](#-contribution)
- [🗺️ Media Servers & Mapping](#-media-servers--mapping)
- [Other](#other)

## 🔓 SDK Libraries

![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> [Streampunk/grandiose](https://github.com/Streampunk/grandiose) - Node.js bindings for NDI
<br />![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> [ykhwong/ppt-ndi](https://github.com/ykhwong/ppt-ndi) - PPT to NDI
<br />![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [keijiro/KlakNDI](https://github.com/keijiro/KlakNDI) - NDI integration in Unity
<br />![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [anome/Unity-plugin](https://github.com/anome/Unity-plugin) - Unity integration for NDI, Syphon, Sprout
<br />![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [ue4plugins/NdiMedia](https://github.com/ue4plugins/NdiMedia) - NDI integration in Unreal Engine
<br />![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/apple.svg" height="14"> [Syphon](http://syphon.v002.info/) - Listed here for posterity, Syphon is an NDI-like SDK to share video between applications on macOS (local only)
<br />![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> + Linux [Godot NDI](https://github.com/unvermuthet/godot-ndi) - Integrates the NDI SDK with the Godot Game Engine

## 🛠️ Converters & Tools

![Price free](https://img.shields.io/badge/price-free-brightgreen) ️️✉️ <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [NewTek NDI tools](https://www.newtek.com/ndi/tools/) - the must-have toolset from NewTek
<br />![Price free](https://img.shields.io/badge/price-free-brightgreen) ✉️ <img src="./media/windows.svg" height="14"> [MediaLooks NDI to SDI converter](https://www.medialooks.com/products/) - converts from NDI to SDI
<br />![Price free](https://img.shields.io/badge/price-free-brightgreen) ✉️ <img src="./media/windows.svg" height="14"> [MediaLooks SDI to NDI converter](https://www.medialooks.com/products/) - converts from SDI to NDI
<br />![Price free](https://img.shields.io/badge/price-free-brightgreen) ✉️ <img src="./media/apple.svg" height="14"> [Sienna-TV Free NDI tools](http://www.sienna-tv.com/ndi/freenditools.html) - Includes a monitor app, signal generator app and scan converter
<br />![Price free](https://img.shields.io/badge/price-free-brightgreen) ✉️ <img src="./media/windows.svg" height="14"> [ZEN Computer Services NDI tools](http://zenvideo.co.uk/ndi.htm) - Variety of tools, including an image viewer, gradient generator and more
<br />![Price free](https://img.shields.io/badge/price-free-brightgreen) ✉️ <img src="./media/apple.svg" height="14"> [NDISyphon](hhttps://docs.vidvox.net/freebies_ndi_syphon.html) - Converts from Syphon to NDI and the other way around
<br />![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> + Linux [Vingester](https://github.com/josephdadams/vingester) - browser source ingest tool for NDI
<br />![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> [NSM](https://github.com/mini0/nsm) - NDI Stream Monitor for viewing and monitoring NDI sources
<br />![Price paid](https://img.shields.io/badge/price-$550-red) ✉️ <img src="./media/windows.svg" height="14"> [Second Stream](http://garaninapps.com/secondstream) - second screen software for mobile devices, takes an NDI feed
<br />![Price paid](https://img.shields.io/badge/price-$600-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [RTMP Mini Server](http://garaninapps.com/rtmpminiserver) - converts incoming RTMP streams to NDI
<br />![Price paid](https://img.shields.io/badge/price-dealer-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [Sienna-TV NDI toolset](http://www.sienna-tv.com/ndi/) - a large variety of tools, from routing to monitoring and test signals
<br />![Price paid](https://img.shields.io/badge/price-$150-red) <img src="./media/windows.svg" height="14"> + Ubuntu - [Orfast Multiviewer](https://orfast.com/) - NDI Multiviewer

## 👓 Software Vision Mixers

![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [Open Broadcaster Studio with the NDI Plugin](https://obsproject.com/forum/resources/obs-ndi-newtek-ndi%E2%84%A2-integration-into-obs-studio.528/) - allows NDI input and output from OBS, even from individual sources in OBS
<br />![Price paid](https://img.shields.io/badge/price-$600+-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [Wirecast](https://www.telestream.net/wirecast/) - software video switcher
<br />![Price paid](https://img.shields.io/badge/price-$60+-red) <img src="./media/windows.svg" height="14"> [vMix](https://www.vmix.com/) - software video switcher
<br />![Price paid](https://img.shields.io/badge/price-€9+/yr-red) <img src="./media/windows.svg" height="14"> [VidBlasterX](https://www.vidblasterx.com/) - software video switcher
<br />![Price paid](https://img.shields.io/badge/price-€70/m-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [Livestream Studio](https://livestream.com/studio) - software video switcher
<br />![Price paid](https://img.shields.io/badge/price-€79/m-red) <img src="./media/apple.svg" height="14"> [mimoLive](https://boinx.com/mimolive/) - software video switcher
<br />![Price paid](https://img.shields.io/badge/price-€16+/m-red) <img src="./media/apple.svg" height="14"> [Ecamm Live](https://www.ecamm.com/mac/ecammlive/) - software video switcher

## 🔴 Playback & Recording

![Price paid](https://img.shields.io/badge/price-$1k-red) <img src="./media/apple.svg" height="14"> [ProVideoPlayer 3](https://renewedvision.com/provideoplayer/download/) - Video cue software
<br />![Price paid](https://img.shields.io/badge/price-$400-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [ProPresenter](https://renewedvision.com/propresenter/download/) - Video cue software
<br />![Price paid](https://img.shields.io/badge/price-$300-red) <img src="./media/apple.svg" height="14"> [Mitti](https://imimot.com/mitti/) - Video cue software
<br />![Price paid](https://img.shields.io/badge/price-€16/m-red) <img src="./media/windows.svg" height="14"> [Playdeck](https://www.playdeck.tv/) - Playout software with recording capability
<br />![Price paid](https://img.shields.io/badge/price-dealer-red) <img src="./media/windows.svg" height="14"> [Stream-Labs VPlay 5](https://www.stream-labs.com/en/catalog/Playout_and_CG/VPlay_5_%E2%80%93_multichannel_broadcasting_with_CG) - Playout software with graphics capability
<br />![Price paid](https://img.shields.io/badge/price-€900-red) <img src="./media/windows.svg" height="14"> [Elite](https://www.elementseurope.com/) - Playout animation
<br />![Price paid](https://img.shields.io/badge/price-€84-red) <img src="./media/windows.svg" height="14"> + Linux - [Livemind Recorder](https://livemind.tv/recorder) - Multitrack NDI recorder
<br />![Price paid](https://img.shields.io/badge/price-$89/m-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [Assimilate SCRATCH](https://www.assimilateinc.com/products/) - colorgrading, dailies and finishing with NDI output
<br />![Price paid](https://img.shields.io/badge/price-$325/m-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [Assimilate Live Assist](https://www.assimilateinc.com/products/liveassist/) - video assist tool that captures, records and plays back NDI
<br />![Price free](https://img.shields.io/badge/price-free-brightgreen) Linux - [Dicaffeine](https://dicaffeine.com/) - NDI player and streamer for Linux (Raspberry Pi OS on Raspberry ARM computers and Ubuntu (Xubuntu) on AMD/Intel computers)
<br />![Price free](https://img.shields.io/badge/price-free-brightgreen) Linux - [RaspiNDI ](https://github.com/raspberry-pi-camera/raspindi) - 
RaspiNDI is a simple NDI send library for Raspberry Pi. Works with LibCamera supported Cameras (Raspberry Pi)


## 🖌️ Graphics

![Price free](https://img.shields.io/badge/price-free-brightgreen) <img src="./media/windows.svg" height="14"> [CasparCG](https://github.com/CasparCG/server/releases/tag/v2.3.0-lts-beta.1) - live graphics application, layerbased real-time compositor
<br /> ![Price paid](https://img.shields.io/badge/price-$450-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [NewBlue Titler Live 4](https://newbluefx.com/products/on-air-graphics/titler-live-present/) - live graphics application
<br />![Price paid](https://img.shields.io/badge/price-$250/yr-red) <img src="./media/windows.svg" height="14"> [SuiteCG](https://suitecg.com/) - live graphics application
<br />![Price paid](https://img.shields.io/badge/price-€1.1k-red) <img src="./media/windows.svg" height="14"> [live.score](https://www.live-score-app.com/) - live graphics application for sports graphics


## 📡 Contribution

![Price free](https://img.shields.io/badge/price-free-brightgreen) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [Skype](https://www.skype.com/nl/get-skype/) - video and audio conferencing
<br />![Price paid](https://img.shields.io/badge/price-$1.3k/yr-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [MediaLooks Video Transport](https://www.medialooks.com/video-transport) - Cloud infrastructure for remote NDI contribution and transmission
<br />![Price paid](https://img.shields.io/badge/price-$1k+/yr-red) <img src="./media/windows.svg" height="14"> [BirdDog Cloud](https://www.bird-dog.tv/cloud-overview/) - Cloud infrastructure for remote NDI contribution and transmission

## 🗺️ Media Servers & Mapping

![Price paid](https://img.shields.io/badge/price-€300+-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [Resolume](https://resolume.com/download/) - VJ and projection mapping software
<br />![Price paid](https://img.shields.io/badge/price-€300+-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [ArKaos GrandVJ](https://vj.arkaos.com/) - VJ software
<br />![Price paid](https://img.shields.io/badge/price-€600-red) <img src="./media/apple.svg" height="14"> [Millumin](https://www.millumin.com/v3/index.php) - show control and projection mapping software
<br />![Price paid](https://img.shields.io/badge/price-$17.5k+-red) <img src="./media/windows.svg" height="14"> [Disguise](https://www.disguise.one/en/) - projection mapping and media server software
<br />![Price paid](https://img.shields.io/badge/price-$10k+-red) <img src="./media/windows.svg" height="14"> [Dataton Watchout](https://www.dataton.com/) - projection mapping and media server software
<br />![Price paid](https://img.shields.io/badge/price-dealer-red) <img src="./media/windows.svg" height="14"> [Green Hippo](https://www.green-hippo.com) - projection mapping and media server software
<br />![Price paid](https://img.shields.io/badge/price-dealer-red) [7th Sense](https://7thsensedesign.com/) - projection mapping and media server software

## Other

![Price free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [CVM Eventi Countdown](https://github.com/CVMEventi/Countdown) - Timer software with integrated NDI output
<br />![Price paid](https://img.shields.io/badge/price-$600+-red) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> [TouchDesigner](https://derivative.ca/) - visual development platform for multimedia
<br />![Price_free](https://img.shields.io/badge/price-opensource-brightgreen) <img src="./media/windows.svg" height="14"> <img src="./media/apple.svg" height="14"> <img src="./media/linux.svg" height="14"> [NDI Streamer](https://github.com/alim-zanibekov/ndi_streamer) - Restream NDI as RTSP/RTMP

## Contribute

Feel free to submit a pull-request or issue to get your software on this list.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Floris Porro has waived all copyright and
related or neighboring rights to this work.
