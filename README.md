# Jupyter 3d

This is a collection of tools for creating 3d object using laser cutter and CNC., The code is formatted as python notebook, hence Jupyter name...

### crochet_revolution_surface
Input the profile of a revolution surface to this tool and it will output to you the number of row and the number of stitches in each row so you can create the revolution surface with a crochet.

Here is an exemple for sphere (and an older less generic version of this code)
![Crochetted jungling balls](https://github.com/FlorianDubath/jupyter_3d/blob/main/crochet_revolution_surface/jungling.jpgg?raw=true)

### greyscale_to_surface_3d

This tool take a grey-scale .png image and convert it into a 3d .stl triangulation (the color is interpreted as the height). The result can be opened with blender or directly feed to your favorite CNC program to converting it into g-code. An example of how to create a complex surface is provided.

Here is a screenshot of blender rendering of the example
![3D from .stl](https://github.com/FlorianDubath/jupyter_3d/blob/main/greyscale_to_surface_3d/Screenshot_1.png?raw=true)

### surface_profile

In this tool you input a 3d surface as a function of the horizontal coordinates, it creates a triangular mesh of profiles to be cut with laser and assembled to reconstruct the surface. 
The output are laser cutter friendly .svg files.

Here is a picture of the exemple build out of cardboard
![Cardboard result](https://github.com/FlorianDubath/jupyter_3d/blob/main/surface_profile/example_cardboard.jpg?raw=true)

## Autor

F. Dubath

## License

You are free to re-use and modify the content of this repository, no warranty of any sort. I'd appreciate if you put a link to your realization in the (dedicated issue)[https://github.com/FlorianDubath/jupyter_3d/issues/1]
