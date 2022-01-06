# Marlin2.0.9.3
Ender 5 plus firmware with direct drive (reversed stepper) and SKR Mini E3 V2 and TFT35 3.0

Junction deviation is turned on. You can disable this by uncommenting //DEFINE CLASSIC_JERK. 

Also, this is setup for a Microswiss direct drive and hot end. To revert to stock, reverse stepper direction for E0 and change the filament retraction distance (400mm) in the pause command. Change your hot end back to 275c to preserve the bowden tube.

The speaker is enabled for the board as well.

My esteps and PID tune for the bed and hot end are in here. I highly recommend that you PID tune yours seperately along with calibrating your esteps. I use this tool: https://www.thingiverse.com/thing:4708764
