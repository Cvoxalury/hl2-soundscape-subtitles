# hl2-soundscape-subtitles
The soundscapes in Source 1 games play sounds directly off files, and therefore cannot tie them to subtitles. 
The provided snippet adds a new keyvalue inside "playrandom" block, that lets soundscape makers associate any existing subtitles with the emitted sound, and define their duration on the screen.

Included are: 
* Valve's c_soundscape.cpp with my edits.
* A simple soundscape showing necessary blocks and keys. The sounds and subtitles it uses are from Half-Life 2.

# Credits:
* Valve Software: original c_soundscape.cpp.
* Cvoxalury: the code edits.

This repository is intended to be used under GNU GPLv3 license. 

