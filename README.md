Hemisphere Suite: Alternate Alternate Firmware for Ornament and Crime
===

![My image](https://farm1.staticflickr.com/676/20090774694_b56e557693_b.jpg)

This repo is a fork from https://github.com/Chysn/O_C-HemisphereSuite and holds my experimentations with the o_C + HS
For those who don't know how to compile things, there is a `.hex` file under Release 
Follow the official repo [instructions](https://github.com/Chysn/O_C-HemisphereSuite/wiki#installation) to install it

### modifications
- Remove PONG App
- Add Scope App, a full screen 1 channel oscilloscope with voltage display and bpm sync

### scope app

Its 1 channel scope, so all inputs and outputs from channel 2, 3 and 4 do nothing
- CLOCK input 1 will sync the ticks to the bpm and display the bpm in the app header
- CV input 1 will be drawn in scope area and the voltage will shown in the app header
- CV input 1 is normalized to CV out 1
- Left encoder will zoom in and out


### firmware:

Hemisphere Suite is an open-source project by Jason Justian (aka chysn)

ornament**s** & crime**s** is a collaborative project by Patrick Dowling (aka pld), mxmxmx and Tim Churches (aka bennelong.bicyclist) (though mostly by pld and bennelong.bicyclist). it **(considerably) extends** the original firmware for the o_C / ASR eurorack module, designed by mxmxmx.

### hardware:

eurorack / teensy 3.2 DAC8565 quad 16bit CV module w/ OLED display

14HP, depth ~ 25mm

build guide: http://ornament-and-cri.me/

