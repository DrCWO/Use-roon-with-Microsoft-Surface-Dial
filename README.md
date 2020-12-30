Use-roon-with-Microsoft-Surface-Dial
====================================

The Music Server roon can be easily enhanced with so called Extensions, plugging
into roon and being operated within the roon gui on a PC or any other device.
Roon Extensions can be run on the music server itself or on a separate PC e.g.,
a Raspberry Pi. They all base on the official [roon
API](https://github.com/RoonLabs/node-roon-api) released for node.js. The
downside of this approach is that for people, uneducated in programming, it is
difficult to use the already offered roon Extensions.

My approach is to offer [rooExtend](https://rooExtend.com/), a ready to use
Raspberry Pi image where useful roon Extensions will be already preinstalled.
The image simply must be copied to a SD-Card with the
[balenaEtcher](https://www.balena.io/etcher/) Software and plugged into the
Raspberry Pi.

The **rooExtend** image also contains a small web interface to connect the
Raspberry Pi to your local WiFi (see quick installation guide). The Raspberry Pi
also can be connected via ethernet cable to your network.

**rooDial Extension**

The first roon Extension distributed with rooExtend is **rooDial**. For rooDial
the image can be run on a “Raspberry Pi zero w” device. All other future
extension will need a Raspberry Pi 4.

The **rooDial** Extension enables the Raspberry to act as a communication bridge
between the Bluetooth operated [Microsoft Surface
Dial](https://www.microsoft.com/en-us/p/surface-dial/925r551sktgn?activetab=pivot:overviewtab)
and the Music Server roon.

Running the image on the Raspberry Pi creates an extension inside the roon user
interface. With this extension you can map spin and press actions of the Surface
Dial to different functions of roon. For example, you can Stop/Play roon by
pressing the Surface Dial and change volume by spinning the Surface Dial.

The image can be downloaded and setup on the Raspberry Pi for free. Controlling
a dedicated roon playback zone inside roon requires a license. Please find more
details and the download link to the image on the
[rooExtend](https://rooExtend.com/) website. Github doesn’t allow that big files
😉
