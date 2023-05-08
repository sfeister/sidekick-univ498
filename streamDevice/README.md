# streamDevice

Each BeagleBone Black has one or more Arduinos attached. The BeagleBone Black sends commands and receives data from the Arduino(s) via USB.

USB serial communication is translated to and from EPICS process variables via an EPICS module called [StreamDevice](
http://epics.web.psi.ch/software/streamdevice/).

"streamDevice" settings files for each EPICS input/output controller (running on the BeagleBone Black) are contained in this folder.