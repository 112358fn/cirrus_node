# Nodes of Sensor Cirrus
On Sensor Cirrus nodes are basically a microprocessor that has attached sensors and an XBee End-Device

## Files
The files are organized in this way

1. Arduino UNO:
  * Firmware: Arduino code for the node and the configuration files of Coordinator and End-Device Xbees(those files has to be uploaded to the XBees through the XCTU software)
  * Shield: A simple shield so SHT17 can be welded and the board XBTS from IT&T can be conected directly. These board was made on Eagle 7.6 Freeware License
  
2. Arduino PRO:
  * Firmware: (Same as Arduino UNO) but this firmware uses a SHT15 sensor so the libraries are diferent.

3. Doc: Various documentation files that can be useful for undertandig or for further development
  
