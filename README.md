# HamShield for Beken BK4811

This is a fork of the Hamshield to support the BK4811 as the Auctus 1846S /RDA1846 transcever dont have access to pre-emphasis I am also looking at a further fork for the BK4816 that also breaks out the I/Q which is needed for digital modulation such as psk

You can purchase HamShield (as well as smaller variants or LoRa version) at http://www.enhancedradiodevices.com/


WARNING: The dev branch is not guaranteed to work. Please use caution if you choose to use that branch. 

# HamShieldBK4811 Arduino Library and Example Sketches

This repository is meant to be checked out into your Arduino application's libraries folder. After reloading the application, the library and example sketches should be available for use.

For overview, help, tricks, tips, and more, check out the wiki: 

https://github.com/EnhancedRadioDevices/HamShield/wiki

# KISS and AFSK

We've moved the KISS and AFSK code to a separate library to help keep memory usage in simple sketches down. To use the AFSK examples, please also install these libraries:

- https://github.com/EnhancedRadioDevices/DDS
- https://github.com/EnhancedRadioDevices/HamShield_KISS

This is a work in progress and the Beken code has not yet been uploaded 
