
<b>This is the repository of the TeensyBat V1_3 development released on 20210909<br>
  This is not a "full" release but a development update. The available code will support both the Teensy 3.6 and the Teensy 4.1</b>

All provided sourcecode can be used directly in platformIO. The sourcecode should compile in any Arduino IDE environment but will need carefull setup of libaries. In PlatformIO all local libraries are in the "lib" subdirectory of the projectfile.  
<br>
<b>HEX</b>: several prebuild HEX files for both Teensy 3.6 and Teensy 4.1<br>

<b>lib/src</b>: source and libraries for PlatformIO (incl platformio.ini)<br>
<b>ZIP</b>: zip file of all source/libraries for PlatformIO<br>

<b>WARNING</b> :If you want to use GPS make sure your module supports serial communication at 115200 baudrate and uses Ublox. We tested using the Beitian 180 and Beitian 220 GPS modules.<br>

<b>WARNING</b> :the available HEX compiled versions have problems at higher (352/384K) samplerates, the sourcecode is updated (20210929)

