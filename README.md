Linux Fork of Armoured Commander

Linux Fork by Brian Weisberg
brianweis999@gmail.com

You must run python2 -m pip install tcod==6.0.7


# Armoured Commander - The WWII Tank Commander Roguelike

#TODO (Short description of game)
Created by: Gregory Adam Scott (sudasana@gmail.com)
Maintained by: Eric Normandeau (eric.normandeau.qc@gmail.com)

http://armouredcommander.com/

## Installation

Minimum screen resolution: 1192 x 732                            

If you get an error when running armcom.exe, trying installing the Microsoft
Visual C++ 2008 Redistributable Package (x86) [vcredist_x86.exe]

If you want to run the game on a smaller resolution, rename the file
`terminal8x12_armcom_small.png` to `terminal8x12_armcom.png`

### Dependencies

Armcom is programmed in Python 2.7.8, and relies on:
- the [Doryen Library (libtcod)](http://roguecentral.org/doryen/libtcod/)
- [PyGame](http://www.pygame.org/download.shtml)

Sound effects created with [LLMS](https://lmms.io/) and
[sfxr](http://www.drpetter.se/project_sfxr.html), and edited with
[Audacity](http://audacityteam.org/).

## Saving Campaigns

- You can only have one campaign game running at one time. If you start a new
  campaign while an old one is unfinished, the old one will be deleted.

## General Tips

- Don't fire at AT Guns, Self-propelled Guns or Tanks unless you're fairly sure
  to take them out. If you fire at their front then they are much more likely
  to fire back at you in the next enemy action phase

- Use Area Fire against unarmoured units at medium range, especially good
  against infantry in cover

- Start with all hatches open, but button up once the ambush and first spotting
  round has passed.

- Keep a balanced mix of HE and AP in the Ready Rack.

- MG fire is really only effective at close range, and at units in the open.

- Every pop-up and console message during a game session is saved to
  logfile.txt; if you find a crash, please send this to me with a description
  of the error

## Legal notice

Copyright 2015-2017 Gregory Adam Scott (sudasana@gmail.com)

This file is part of Armoured Commander.

Armoured Commander is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Armoured Commander is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
    
You should have received a copy of the GNU General Public License
along with Armoured Commander, in the form of a file named "LICENSE".
If not, see <http://www.gnu.org/licenses/>.

xp_loader.py is covered under a MIT License (MIT) and is Copyright (c) 2015 Sean Hagar
see XpLoader_LICENSE.txt for more info.
