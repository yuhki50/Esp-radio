# Esp-radio
Internet radio based on Esp8266 and VS1053.  Will compile in Arduino IDE.  New version 24-may-2017.

WARNING: If you are using V2.4.0 of the core library: set IwIP Variant to "V1.4 Prebuilt" in the Tools of the IDE.

Features:
-	Can connect to thousands of Internet radio stations that broadcast MP3 or Ogg audio streams.
- Can connect to a standalone mp3 file on a server.
- Can connect to a local mp3 file on SPIFFS.
- Support for .m3u playlists.
-	Uses a minimal number of components; no Arduino required.
-	Handles bitrates up to 320 kbps.
-	Has a preset list of maximal 100 favorite radio stations in configuration file.
- Configuration file can be edited through web interface.
-	Can be controlled by a tablet or other device through a build-in webserver.
- Can be controlled over MQTT.
- Can be controlled over Serial Input.
-	Optional one or three button control to skip to the next preset station.
-	The strongest available WiFi network is automatically selected.
-	Heavily commented source code, easy to add extra functionality.
-	Debug information through serial output.
-	20 kB ring buffer to provide smooth playback.
-	SPIFFS filesystem used for configuration of WiFi SSIDs, passwords and small MP3-files.
-	Software update over WiFi possible (OTA).
-	Saves volume and preset station over restart.
-	Bass and treble control.
- Configuration also possible if no WiFi connection can be established.
- Can play iHeartRadio stations.

See documentation in pdf-file.

