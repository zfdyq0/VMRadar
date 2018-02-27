# PUBG-Radar ![Imgur](https://i.imgur.com/n3JtN5d.png)

https://github.com/SamuelNZ/VMRadar/releases

![Imgur](https://i.imgur.com/8MfCXi2.gif)

This version runs without the spoofing shit in a VM.

'Fixed' the item locations, still working on it.

### Key Kinds
You can't filter level 3 gear (always enabled)

#### Item Filter:
* HOME -> Show / Hide Compass
* NUMPAD_0 -> Filter Throwables
* NUMPAD_1 -> Filter Weapon
* NUMPAD_2 -> Filter Attachments
* NUMPAD_3 -> Filter Level 2
* NUMPAD_4 -> Filter Scopes
* NUMPAD_5 -> Filter Meds
* NUMPAD_6 -> Filter Ammo

#### Zooms:
* NUMPAD_7 -> Scouting
* NUMPAD_8 -> Scout/Loot
* NUMPAD_9 -> Looting

### Online Mode:
`java -jar target\pubg-radar-1.0-SNAPSHOT-jar-with-dependencies.jar "Middle PC IP" PortFilter "Game PC IP"`

### Offline Mode:
You can replay a PCAP file in offline mode:

`java -jar target\pubg-radar-1.0-SNAPSHOT-jar-with-dependencies.jar "Middle PC IP" PortFilter "Game PC IP" Offline`

## Build
Using [maven](https://maven.apache.org/) or [JetBrains](https://www.jetbrains.com/idea/)

## Install and Run

1. Install VMWare Workstation
2. Setup your VM in Bridged Mode, replicate physical.
3. Install [JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) on your VM.
4. Install [Wireshark + WinPCap](https://www.wireshark.org/) on your VM
5. Change your IP addresses in the batch file
6. Run as admin and disable full screen optimizations in the Compatibility tab in the Properties.
7. Run the batch file.



