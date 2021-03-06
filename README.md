Conform
=======

**[Get Conform on the App Store.](https://itunes.apple.com/fi/app/conform/id664574539?mt=8)**

**[Watch a demonstration video on YouTube.](http://www.youtube.com/watch?v=nBg02GLqwgs)**

## App Store description

Conform is an interactive composition for iPad, where complexity leads to less control.

You are presented with a normal 8-channel 16-step sequencer. But once you select a step, triggering it will move it to a new position. Additional function buttons modify the step grid further, enabling new creative processes.

Credits:

Programming and sound design by Johan Halin.

Clicks and pops by Otto Hassinen. (http://soundcloud.com/trisector)

Created by Aero Deko.

## Notes

Conform uses [The Amazing Audio Engine](http://theamazingaudioengine.com/), which is installed via [CocoaPods](http://cocoapods.org/). After cloning the repository, remember to do the following:

    pod install
    
Also, remember to open ```conform.xcworkspace``` instead of the xcodeproj.
    
The project was initially created in 2010, and has been developed very sporadically since then. The sequencer was originally based on NSTimer, which was not very useful. (I bet this comes as a huge surprise) After discovering The Amazing Audio Engine in 2013, I decided to get off my ass and actually finish the app. My personal deadline was set at the end of my summer vacation, which means that the code is a bit messy since it's quite rushed in parts. Constructive criticism and pull requests (especially around the audio stuff) is very welcome.

If you do contribute code (or anything else) to the project, I'd be happy to credit you in the app and elsewhere.

The sample sequencer and synth will probably be separated into something else at some point in the future, since I'll be using them in other projects.

## Screenshots

![Screenshot 1](http://a4.mzstatic.com/us/r1000/005/Purple4/v4/fb/fc/13/fbfc1358-bda9-e06c-600e-b01a23cf9286/mzl.ykmaedml.480x480-75.jpg)

![Screenshot 2](http://a3.mzstatic.com/us/r1000/009/Purple4/v4/3c/81/94/3c819406-fe2a-c07a-8497-9356c0d7d59d/mzl.ubqsaunl.480x480-75.jpg)

![Screenshot 3 - default state](http://a1.mzstatic.com/us/r1000/009/Purple/v4/d7/06/64/d70664fe-c4a8-cc5f-d7e3-bdd376d1f399/mzl.gytagvkb.480x480-75.jpg)
