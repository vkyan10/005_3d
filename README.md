# 005_3d
Add the following commands to the parser
- clear: clears the edge matrix of all points
- box: adds a rectangular prism (box) to the edge matrix - takes 6 parameters (x, y, z, width, height, depth)
  - drawn with 12 lines drawing the edges
- sphere: adds a sphere to the edge matrix - takes 4 parameters (x, y, z, radius)
  - drawn as the points on the surface
- torus: adds a torus to the edge matrix - takes 5 parameters (x, y, z, radius1, radius2)
  - radius1 is the radius of the circle that makes up the torus
  - radius2 is the full radius of the torus (the translation factor) - the center of the torus to the center of any circular slice of the torus
  - drawn as the points on the surface
