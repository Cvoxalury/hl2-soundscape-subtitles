# hl2-soundscape-subtitles
The soundscapes in Source 1 games play sounds directly off files, and therefore cannot tie them to subtitles. 
The provided snippet adds a new keyvalue inside "playrandom" block, that lets soundscape makers associate any existing subtitles with the emitted sound, and define their duration on the screen.

*Note*: this code was more thoroughly tested in SDK Base 2013 *Singleplayer*. It *should* work in *Multiplayer*, but only a brief test compile in the MP codebase was performed.

Included are: 
* Valve's c_soundscape.cpp with my edits.
* A simple soundscape showing necessary blocks and keys. The sounds and subtitles it uses are from Half-Life 2.

# Credits:
* Valve Software: original c_soundscape.cpp.
* Cvoxalury: the code edits.

This repository is intended to be used under MIT license. Basically: do whatever. 

