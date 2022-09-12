# c++RayTracer

This Ray Tracer was written with raw c++, and uses different rendering techniques such as anti-aliasing, camera depth of field, and normal calculation (can later be used to implement reflections and diffuse shaders).

A couple of example images are provided, with different levels of detail. One in 1440p with 100x anti-aliasing and another in 4k with 300x anti-aliasing.

In order to run the code yourself, compile the source files with a c++ compiler, and then run the .exe from the command line. To write to a file, run the .exe in the command line and use the command > filename.ppm to write to a file. Then, use an online ppm viewer (https://www.cs.rhodes.edu/welshc/COMP141_F16/ppmReader.html) to convert the image file into a png.
