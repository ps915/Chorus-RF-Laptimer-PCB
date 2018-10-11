# Chorus-RF-Laptimer-PCB
4in1 PCB for the Chorus RF Laptimer by Andrey Voroshkov
https://github.com/voroshkov/Chorus-RF-Laptimer

<img src="https://raw.githubusercontent.com/ps915/Chorus-RF-Laptimer-PCB/master/p3.JPG" width="350"> <img src="https://raw.githubusercontent.com/ps915/Chorus-RF-Laptimer-PCB/master/p1.JPG" width="350">

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/avLRJ5z0UP4/0.jpg)](https://www.youtube.com/watch?v=avLRJ5z0UP4)

https://www.youtube.com/watch?v=avLRJ5z0UP4

# Features
* PCB for 4 Nodes (4 Pilots)
* easy extendable via JST XH cable (8 Pilots)
* 5V stepdown for Arduinos
* adjustable stepdown for RX Modules (use 3.5V to keep temperature low)
* 92 x 92mm mounting holes
* XT60 PowerIn
* 5V USB PowerIn (if you want to use a powerbank)
* stacked hardware - can be changed in seconds
* Buzzer Port to connect one Buzzer per Node

# Changelog
### [ALL RELEASES](https://github.com/ps915/Chorus-RF-Laptimer-PCB/releases) 
### 22.05.2018 - v3.1 beta released [DOWNLOAD](https://github.com/ps915/Chorus-RF-Laptimer-PCB/files/2025616/chorus_4in1_3.1_gerber_file.zip)
* inital release
* i did not tested this PCB. To V3.0 i just added the Diodes and did cleaned it up a bit. V3.0 worked so far. Please report any issues!

# Important
#### up to 4 nodes
You can also just use one or two nodes. All you haveto do is bridge TX/RX (see on silkscreen) of the other nodes
Always use at least "Node1" because the voltage measurement is connected to this node.
#### 5V power via USB
if you want to power the unit via 5V USB, please remove stepdown "Arduino" and bridge IN and OUT.
#### connect 2 or more PCBS
If you plan to connect more PCBS together, please always set the Loopback Jumper to the first PCB
Then connect the next PCB via 6Pin wire. On the first PCB, bridge MV. On following PCBs please bridge GM. WiFi Module always connects to the last PCB.
<img src="https://raw.githubusercontent.com/ps915/Chorus-RF-Laptimer-PCB/master/p5.jpg">

# What do you need (4 nodes)
* 1x 4in1 PCB
* 4x [Arduino Pro Mini](https://www.banggood.com/Wholesale-New-Ver-Pro-Mini-ATMEGA328-328p-5V-16MHz-Arduino-Compatible-Nano-Size-p-68534.html?p=3R26141006882201412N)
* 4x [RX5808 (with SPI mod)](https://www.banggood.com/FPV-5_8G-Wireless-Audio-Video-Receiving-Module-RX5808-p-84775.html?p=3R26141006882201412N)
* 12x 100 ohm 1206 SMD Resistor
* 4x 1k ohm 1206 SMD Resistor
* 1x 10k 1% ohm 1206 SMD Resistor
* 1x 1k 1% ohm 1206 SMD Resistor
* 4x [1n5817 smd 1A 20V do-214ac Schottky diode](https://de.aliexpress.com/item/Free-shipping-100pcs-sma-1n5817-smd-1A-20V-do-214ac-Schottky-diode-SOt-23-diode-ss12/32337976826.html)
* 2x [6 Pin JST XH 90° Connector](https://de.aliexpress.com/item/100Pcs-2-54Mm-Spacing-series-Right-Angle-Bend-the-foot-Jst-Xh-Connector-Pin-Header-White/32819782475.html?spm=a2g0s.9042311.0.0.27424c4dqFzf6o)
* 1x [USB Breakout Board](https://de.aliexpress.com/item/10PCS-CJMCU-Breakout-Power-Supply-Module-Micro-USB-Interface-Power-Adapter-Board-USB-5V-Breakout-Module/32789480622.html?spm=a2g0s.9042311.0.0.27424c4dxZJ1Gy)
* 2x [Pin Jumper](https://www.banggood.com/100pcs-2_54mm-Jumper-Cap-Short-Circuit-Cap-Pin-Connection-Block-p-1212414.html?p=3R26141006882201412N)
* 1x [DT-06 WiFi Module](https://www.banggood.com/Geekcreit-DT-06-Wireless-WiFi-Serial-Port-Transparent-Transmission-Module-TTL-To-WiFi-p-1141047.html?p=3R26141006882201412N)
* 1x [5V Stepdown](https://www.banggood.com/5pcs-DC-DC-5V-3A-Power-Supply-Module-Buck-Step-Down-Regulator-Module-24V-12V-9V-To-5V-Fixed-Output-p-1198421.html?p=3R26141006882201412N)
* 1x [adjustable stepdown](https://www.banggood.com/5Pcs-Mini-DC-DC-Converter-Adjustable-Power-Supply-Step-Down-Module-p-951165.html?p=3R26141006882201412N)
* optional [6Pin JST XH cable](https://de.aliexpress.com/item/20-Pcs-10cm-6Pin-JST-XH-Connector-Cable-Wire-2-54mm-Pitch-Female-to-Female/32767693655.html?spm=a2g0s.9042311.0.0.27424c4dSbC1ad) for connecting two or more PCBs together
* [1x XT60](https://www.banggood.com/Amass-XT60-MaleFemale-Bullet-Connector-Plugs-For-RC-Lipo-Battery-p-929670.html?p=3R26141006882201412N)
* 4x 3Pin Pin Header Socket
* 4x 6Pin Pin Header Socket
* 4x 12Pin Pin Header Socket
* 16x 2Pin Pin Header Socket
* manny Pin Header RM 2.54

(some links are affiliate links)

# Software
https://github.com/voroshkov/Chorus-RF-Laptimer

# Ordering PCB
you can order the PCB in china:
1. Go to [www.seeedstudio.com](https://www.seeedstudio.com/fusion_pcb.html#utm_source=seidel-philipp.de&utm_medium=banner)
2. Upload gerber file
3. choose PCB color
3. add to cart
4. order

Detaild Tutorial how to order from seeedstudio [here](https://blog.seidel-philipp.de/do-it-yourself-pagoda-fpv-antenna-for-less-than-2/)

