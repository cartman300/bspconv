# bspconv
Quake bsp map converter tool

![Image](/screenshots/a.png)

Tested on maps from https://lvlworld.com/
I did not encounter any that do not work yet. If you do, please create a new issue.

Currently only Quake 3 (IBSP 46) and Quake Live (IBSP 47) maps are supported.

Some maps may have missing textures, that's because they reference textures in the original Quake 3 pak0.pk3. You have to copy these manually for now, may add a feature to list them on conversion time or even automatically extract them from a supplied pk3. You can check which are missing in the console when you start the map.

Feature requests welcome.