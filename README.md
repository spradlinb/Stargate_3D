# Stargate_3D
Arduino code used to build the Stargate lights and sounds for a 3D build.

Original 3D model files can be found here: 
https://www.printables.com/model/560402-stargate-with-iris-80cm-in-diameter

My altered files, to allow easier placement of the LED strings, can be found here: 
https://www.printables.com/model/688291-stargate-modified-chevron-parts

Addressable LED lights used are called "Chasing Dream Full Color Twinkle Decorative" on Amazon: 
https://www.amazon.com/dp/B0BVZLWQ2T

The Arduino hardware used is the NodeMcu Mini D1. It's a WiFi enabled board, which is far more powerful than this build required. But it's small and was in my parts bin to use. It also allows future upgrades to use the WiFi option for IoT control, if desired.

The MP3 player is the DFPlayer Mini module, which you can get from many places. It requires a MicroSD card. Files must be named in a specific way and uploaded in the order you intend to reference them in code, or it won't work correctly.

I only used one speaker, but the module can support two for stereo sound if desired. These have been the best speakers that don't sound tinny when used: 
https://www.amazon.com/gp/product/B0BTP67F81

The button to activate the lights and sounds can be any momentary tactile button switch. I used a 6x6x5mm momentary tactile button switch.

Power is provided by a 5V plug-in adapter and power jack wired to the arduino and MP3 module. It was important to make sure the MP3 module had the shortest wiring to the power supply as possible, and not pulling power directly from the Arduino. 

I'm not including a wiring diagram here, but I have included three photos of the prototype board and wiring. The only piece missing there is the second LED connector. The pin numbers in the Stargate.ino will indicate what wires were used for the button (D2), LEDs (D7 for Chevrons, D8 for wormhole glow), and MP3 (D5 and D6) connections. DFPlayer Mini wiring can be found online for instructions. 
