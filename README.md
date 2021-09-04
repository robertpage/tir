![Start screen for game](https://robertpage.github.io/tir/screenshot.png)

# Tir: Alone

## [PLAY](https://robertpage.github.io/tir/)

My entry for jsk13 2021. Explore the vastness of space as a probe trying to spread the knowledge of a lost earth.

# About
Made to be self contained in a SVG and then embeded via an object tag. The game randomly generates a map at start. I believe traveling from one side of the map to the other takes about 7-ish hours without ship upgrades. There are special things to find and generic celestial bodies. Arrow keys control movement and scanning/communicating with objects. I think I could have gotten this much smaller without a ton of work but it was already under 13k so 🤷‍♀️. For music Tir includes a thoroughly mangled version of [TinyMusic](https://github.com/kevincennis/TinyMusic). An absolutely phenomenal music player! The music itself is randomly generated. Arrow keys control ship movement, and 'M' toggles music.

# Story
The earth has gone dark. A probe was sent out to find intelligent life and tell them our story so that we can live on in their memories.

# Add the game to a site
Change the path to the tir.svg data attribute and add it to a webpage. The width and height set in the style attribute can really be any size but the experience is best the larger it is.
```
<object style="width:100%;height:calc(100vh - 20px)" type="image/svg+xml" data="tir.svg">Oops, something went wrong :-/</object>
```