# AmbientSounds

AmbientSounds is an ambient sound player inspired by Noizio, A Soft
Murmur, etc...

This repository only contains the audio files used by AmbientSounds.
For now, two frontends are available : a
[curses frontend](https://github.com/Muges/ambientsounds-curses) for
linux, and a
[Firefox OS app](https://github.com/Muges/ambientsounds-curses) (which
is also usable on android).

## Sounds

The original sound files are listed below.

- [Fireplace by inchadney](http://www.freesound.org/people/inchadney/sounds/132534/) (CC0)
- [Heavy Rain by D W](http://www.freesound.org/people/D%20W/sounds/136971/) (CC BY)
- [Forest Rain by Corsica_S](http://www.freesound.org/people/Corsica_S/sounds/169031/) (CC BY)
- [Stream by mystiscool](http://www.freesound.org/people/mystiscool/sounds/7138/) (CC BY)
- [Thunderstorm by RHumphries](http://www.freesound.org/people/RHumphries/sounds/2523/) (CC BY)
- [Wind by felix.blume](http://www.freesound.org/people/felix.blume/sounds/139337/) (CC0)

To add new sounds, you just need to create an ogg file of a few
minutes (preferably less than 5) that loops seamlessly, and set the
title tag correctly. Creating a seamless loop is pretty easy with
natural sounds, I personally use
[audacity](http://audacity.sourceforge.net/), with
[this method](http://manual.audacityteam.org/o/man/tutorial_looping.html)
to extract a segment that loops without clicking, or
[this one](http://www.wearytaffer.com/tutorials/tut_loops.html) to
fade the beginning and the end of the track. You can also modify the
tags when you export an ogg file with audacity.

If you want me to add your sound to the AmbientSounds, you can make a
pull request or open an issue. This program is a free software, and will
only contain free sounds, with licenses such as CC0, CC BY, CC BY-SA
(and not CC BY-NC or CC BY-ND).
