Strife: Veteran Edition GPL Source Code
=======================================
Copyright 2016, Night Dive Studios, Incorporated.

This file contains the following sections:

GENERAL NOTES
LICENSE

GENERAL NOTES
=============

Game data and patching:
-----------------------

This source release does not contain any game data, the game data is still
covered by the original EULA and must be obeyed as usual.

Note that Strife: Veteran Edition is available from the Steam store at
http://store.steampowered.com/app/317040/


Compiling on Win32:
-------------------

A project file for Microsoft Visual Studio 2008 is provided in 
msvc/chocolate.sln 
The solution file is compatible with the Express releases.

Compiling on MacOS 10.x:
-------------------

A project file for XCode is provided in xcode/Chocolate/Strife-VE.xcodeproj
All dependencies and settings should already be set inside the workspace.

Compiling on Linux:
-------------------

A CMake build system has been added in version 1.3, and is currently up-to-date.

A project file for Codeblocks is provided in codeblocks/chocolate.workspace
Before compiling, be sure to compile patchelf first by going into the patchelf/
directory and then running configure and then make. The project has not been
updated for 1.3, so some source files may need to be added before you can 
build successfully.

Codeblocks uses a post-build step that calls patchelf to set up runtime paths
for the output executable.

Trademark disclaimers:
----------------------

The source code may make reference to the following trademarks:

"DOOM" is a trademark of ZeniMax Media, Incorporated.
"Heretic" and "Hexen" are trademarks of Raven Software, Incorporated.
"Strife: Veteran Edition" is a trademark of Night Dive Studios, Incorporated.

No license for use or transfer of ownership in any trademark is implied or
should be construed.


Steam and GOG Galaxy:
---------------------
The Strife: Veteran Edition GPL Source Code release does not include 
functionality for integrating with Steam or GOG Galaxy.  This includes roaming
profiles, achievements, leaderboards, matchmaking, the overlay, or any other 
Steam or Galaxy features.  It may be necessary to undefine the `_USE_STEAM_` or
`GOG_RELEASE` symbols in build scripts or project files in order to compile.


Other platforms, updated source code, security issues:
------------------------------------------------------

If you have obtained this source code several weeks after the time of release,
it is likely that you can find modified and improved versions of the engine in
various open source projects across the Internet.

Depending on your interest with the source code, those may be a better starting
point.


LICENSE
=======

The Strife: Veteran Edition source code is available under the terms of the GNU
General Public License v2.0

See COPYING.txt for the GNU GENERAL PUBLIC LICENSE

FFmpeg
------
FFmpeg is used under the terms of the LGPL v2.1; see COPYING-LGPL.txt.

SDL
---
SDL, SDL_mixer, and SDL_net are used under the terms of the LGPL v2.1; 
see COPYING-LGPL.txt.


EXCLUDED CODE: The code described below and contained in the Strife: Veteran 
Edition GPL Source Code release is not part of the Program covered by the GPL 
and is expressly excluded from its terms.  You are solely responsible for 
obtaining from the copyright holder a license for such code and complying with
the applicable license terms.

libpng
-------------------------------------------------------------------------------
libpng version 1.6.12 - June 12, 2014
Copyright (c) 1998-2014 Glenn Randers-Pehrson
 (Version 0.96 Copyright (c) 1996, 1997 Andreas Dilger)
 (Version 0.88 Copyright (c) 1995, 1996 Guy Eric Schalnat, Group 42, Inc.)

The PNG Reference Library is supplied "AS IS".  The Contributing Authors
and Group 42, Inc. disclaim all warranties, expressed or implied,
including, without limitation, the warranties of merchantability and of
fitness for any purpose.  The Contributing Authors and Group 42, Inc.
assume no liability for direct, indirect, incidental, special, exemplary,
or consequential damages, which may result from the use of the PNG
Reference Library, even if advised of the possibility of such damage.

Permission is hereby granted to use, copy, modify, and distribute this
source code, or portions hereof, for any purpose, without fee, subject
to the following restrictions:

  1. The origin of this source code must not be misrepresented.

  2. Altered versions must be plainly marked as such and must not
     be misrepresented as being the original source.

  3. This Copyright notice may not be removed or altered from
     any source or altered source distribution.

The Contributing Authors and Group 42, Inc. specifically permit, without
fee, and encourage the use of this source code as a component to
supporting the PNG file format in commercial products.  If you use this
source code in a product, acknowledgment is not required but would be
appreciated.

zlib
-------------------------------------------------------------------------------
version 1.2.7, May 2nd, 2012

Copyright (C) 1995-2012 Jean-loup Gailly and Mark Adler

This software is provided 'as-is', without any express or implied
warranty.  In no event will the authors be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:

1. The origin of this software must not be misrepresented; you must not
   claim that you wrote the original software. If you use this software
   in a product, an acknowledgment in the product documentation would be
   appreciated but is not required.
2. Altered source versions must be plainly marked as such, and must not be
   misrepresented as being the original software.
3. This notice may not be removed or altered from any source distribution.

-------------------------------------------------------------------------------
