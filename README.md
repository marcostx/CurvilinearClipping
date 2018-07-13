# Isosurfaces cuts

In this work the task and implement the Curvilinear Cuts algorithm. In this approach, instead of calculating Phong's illumination when we find a valid point P  of the object, we check if D (P)> t, where t is an established threshold and, if so, we return the brightness of the image in P. This way we can visualize the texture of cut isosurfaces of an object.

## Getting Started

### Prerequisites

This project is built using the functions of the IFT library. Here we use the compiled lib for Mac. GCC and CMake are the most important prerequisites for this project.


### Compiling


```
make CL
```


## Running
```
./CL        input.csn
            input-label.scn
            output-image.png
            tilt
            spin
            threshold
```


where output-image.png is the output file, which will be generated at the end of the program in the data folder, tilt and spin are the angles for projection and thresh is the threshold distance value to cut the surface.


## Authors

* **Marcos Teixeira** - (https://github.com/marcostx)

## Details

For more details on theory, implementation and results, read the report  **report4_mo815.pdf**.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Prof. Alexandre Falcão - UNICAMP
