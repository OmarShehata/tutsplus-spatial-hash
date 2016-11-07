### Tuts+ Tutorial: Redesign Your Display List With Spatial Hashes

#### Instructor: Omar Shehata

A common way to organize your game objects is by putting them all into one big sorted list. This can be very inefficient once you have a large game world where most objects are off-screen. Here, I'll show you an easy way to solve that by storing your objects spatially.

Source files for the Tuts+ tutorial: [Redesign Your Display List With Spatial Hashes](http://gamedevelopment.tutsplus.com/tutorials/redesign-your-display-list-with-spatial-hashes--cms-27586)

### Usage

Open `traditional_render.html` in the browser to see the slow version, running 1 million objects in the world with everything in a single display list. 

Open `spatial_hash.html` in the browser to see the fast version, also a million objects, but using a spatial hash to calculate what to draw instead of looping through a giant array.
