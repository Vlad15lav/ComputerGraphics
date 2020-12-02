# Computer Graphics
Basic topics from computer graphics

` TODO: Rendering OpenGL `

1. Geometry description.
2. Displaying the model as polygons. The Algorithm Bresenham.
3. Animation creation, affine transformations.
4. Bezier curves.
5. Bezier clock.
6. Rendering 3D model. OpenGL.

## Obj format notation
Obj file - Utah Teapot model:</br>
1. The list of vertices - "v" market
2. Facets - "f" market

The program finds: number of vertices and faces, max and min values of (x, y, z) and the surface area.</br>
![](/NotationObj/teapot.png)
## Algorithm Bresenham
Drawing of the teapot using the algorithm Bresenham.</br>
![](/Bresenham/teapot.png)
## Animation gif
Create rotation animations, zoom, and color changes. Affine transformation.
Download ffmpeg.exe to create gif or mp4 animations. On the developer's website.</br>
![](/Animation/teapot_anim.gif)
## Bezier curves
Create an animation of changing digits (0-9) based on Bezier curves.</br>
![](/BezierСurve/digits_anim.gif)
## Bezier clock
Creating the Bezier clock.</br>
![](/Clock/clock_anim.gif)
## Rendering 3D model. OpenGL
Rendering 3d model, OpenGL annotation.

Reference Coordinates in 3-d graphics:
- Local space
- World space
- View space
- Clip space
- Screen space
![](/OpenGL/spaces.png)

Culling of invisible faces
- Scalar product of the camera vector and the normals to the face.
- Z-buffer

Texture overlay
- Texture coordinates (vt)
- Interpolation of barycentric coordinates

Lighting with the Phong reflection model
- Ambient, Diffuse, Specular
- Lighting attenuation

Rendering
- Wire model
- Model with faces (gray color)
- Model with textures
- Model with lighting
- Model with textures + lighting
