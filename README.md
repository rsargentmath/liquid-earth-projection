# The Liquid Earth projection

The Liquid Earth projection is a new, nearly equal-area map projection. It has exceptionally low distortion on landmasses (including islands), while maintaining a mostly north-up orientation and a familiar, symmetrical shape. For a more detailed description of the projection, see https://rsargentmath.github.io/liquid_earth.

This repository includes npy and csv files for the meshes that the projection uses, as well as svg and png templates. All of these files are in the public domain, though credit is appreciated.

`Liquid_Earth_mesh_verts_initial` and `Liquid_Earth_mesh_verts_transformed` are the arrays of the vertices of the initial mesh and transformed mesh respectively. These vertices are represented with a right-handed Cartesian coordinate system. `Liquid_Earth_mesh_tris` describes the triangles of both meshes. Each triangle consists of three indices into the vertex arrays. The vertex arrays are 0-indexed and each triangle lists the vertices in anticlockwise order.