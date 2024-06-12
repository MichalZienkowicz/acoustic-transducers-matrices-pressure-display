# acoustic-transducers-matrices-pressure-display
App allowing for calculation and display of pressure generated by acoustic transducer matrices of desired parameters for modeling a two phased array acoustic levitator.

## About the app
The application's purpose is to allow for the modeling of an acoustic levitation device with desired transducer characteristics and geometrical parameters. The application calculates pressure at every point of a grid. The number of points creating the grid can be adjusted by the user. Based on the given focus point coordinates, phases for each transducer are calculated in a way that ensures waves coming from the individual transducers have their nodes at the focus point. This allows the pressure to build up in a way required for acoustic levitation at any point between the arrays.

The application can be used to calculate phases of transducers for a set of focus points, creating a desired path. These phases could then be fed to real acoustic levitator software, enabling the movement of a levitating particle corresponding to the created path (in a fashion similar to acoustic volumetric display devices).

Currently, saving pressure data and phases of array elements is not yet implemented. Additionally, acoustic transducers are modeled as omnidirectional sound sources, which is to be changed since ultrasonic transducers used for acoustic levitation are highly directive sound sources.

## Interface
![image](https://github.com/MichalZienkowicz/acoustic-transducers-matrices-pressure-display/assets/123846504/f576c595-ff3e-47c9-ac3a-f5f95b880a49)
