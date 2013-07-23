three.js-normal-map-0
=====================

A demo of a normal map in three.js, showing some problems and solutions:

**Getting normals to work**

- [With no normal texture, showing "twisted" normals](http://meetar.github.io/three.js-normal-map-0/index0.html)

I asked: "Why do these normals look twisted?"
http://stackoverflow.com/questions/17453298/twisted-normals-with-the-three-js-normal-shader-r-58

- [Using a flat normal texture](http://meetar.github.io/three.js-normal-map-0/index2.html) - correct normals

**Adding a displacement map**
- [Using a displacement map](http://meetar.github.io/three.js-normal-map-0/index3.html) - normals are still flat

I asked: "Can normals be recalculated post-displacement?" http://stackoverflow.com/questions/17528878/compute-normals-from-displacement-map-in-three-js-r-58

- [Recalculating post-displacement normals in the fragment shader](http://meetar.github.io/three.js-normal-map-0/index6.html) - hard edges only

- [Recalculating post-displacement normals with JavaScript](http://meetar.github.io/three.js-normal-map-0/index14.html) - smoothed

**Getting specular right**

- [Flat normal map with disconnected specular](http://meetar.github.io/three.js-normal-map-0/spec01.html)
- [Flat normal map with correct specular](http://meetar.github.io/three.js-normal-map-0/spec02.html) - had to use pointVector instead of pointHalfVector as in many examples.

**Getting normals from displacement map**

- [Displacement map used as a bump map](http://meetar.github.io/three.js-normal-map-0/bump.html) - using pieces of the normalmap and phong shaders, showing noisy but correct normals. This uses Morten Mikkelsen's method of taking the derivative of the heightmap: http://mmikkelsen3d.blogspot.sk/2011/07/derivative-maps.html
