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

**Using displacement map as a bump map**

- [Displacement map used as a bump map](http://meetar.github.io/three.js-normal-map-0/bump.html) - using pieces of the normalmap and phong shaders