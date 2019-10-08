---
title: Dev stuff
created: '2019-10-08T06:18:12.646Z'
modified: '2019-10-08T06:19:44.668Z'
---

# Dev stuff

### Sylvains animation tipps:

start with Illustrator, export the «finished» illustration in svg, then I cleanup manually the svg within a text editor. You could then revert your animation and do a «explosion», start with the regrouped state and move then each part randomly. And finally revert the whole animation.
That means that your pieces in the final regrouped state have all ‘transform’ set to 0 (xy values are defined in illustrator). You can then set manually random ‘transform’ values for the initial exploded state

Yep. And another advice: Try to play only with ‘transform’ values (translate, rotate, scale) or opacity. Avoid transitions on margins, top or left or padding
