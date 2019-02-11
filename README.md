# Computer-Graphics-Assignments
Assignments done as part of [Graduate Computer Graphics, CSCI-GA 2270-001 Fall 2018](https://github.com/danielepanozzo/cg) at New York University. Tools used : C++, OpenGL, [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page)

## Assignment 1
A raytracer was written, and used to render spheres and more complex triangulated surfaces. Exact features implemented:
* Simple lambertian lighting using Orthogonal projection<br/>
![Image1](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Assignment1_1.png)
* Ambient and Specular lighting<br/>
![Image2](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Assignment1_2.png)
* Perspective projection<br/>
![Image3](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Assignment1_3.png)
* Shadows cast by the primary light source<br/>
![Image4](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Assignment1_4.png)

## Assignment 2
A 2D editor was implemented for vector graphics. All operations were performed on the GPU i.e., shader code was written to handle the triangle manipulations.

* Triangles can be added, deleted and edited by all the basic matrix operations(rotation, translation, rescaling). <br/>
![Gif1](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Asg2_1.gif)
* Custom colors can be assigned to each vertex.<br/>
![Gif2](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Asg2_2.gif)
* Camera can be panned, zoomed-in and -out.<br/>
![Gif3](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Asg2_3.gif)
* Bezier curves can be added and the control points moved.<br/>
![Gif4](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Asg2_4.gif)

## Assignment 3
A 3D editor was implemented that allows to prepare 3D scenes composed of multiple 3D objects. 

* 3D meshes of cube, bumpy cube and bunny can be manipulated interactively, user can add, edit, and delete 3D meshes. All operations were performed on the GPU i.e., shader code was written to handle the triangle manipulations.<br/>
![Gif31](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Asg3_1.gif)

* Clicking on a object will select the object, changing its color. It can then be edited by all the basic matrix operations(rotation, translation, rescaling).<br/>
![Gif32](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Asg3_2.gif)

* Each object also has an editable rendering setting: Wireframe, Flat Shading and Phong Shading.<br/>
![Gif33](https://github.com/bhavanibhamidipaty/Computer-Graphics-Assignments/blob/master/Asg3_3.gif)

