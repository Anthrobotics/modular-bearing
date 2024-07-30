![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/banner.jpg?raw=true)

# modular-bearing
A lightweight, customizable and parametric bearing, manufacturable using 3D printing and CNC machining.

# Description
The modular bearing is designed as an alternative for non-replaceable (or difficult to replace) bearings in robotic joints and actuators. It is customized using an OpenSCAD generator, and can be used in a wide number of designs. It can be swapped out without requiring any tools, depending on how it is integrated into a design.

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/mod-bearing-iso-view.png?raw=true)

# Specifications
The following parameters of the modular bearing can be customized:
- Outer diameter (OD)
- Inner diameter (ID)
- Width
- Number of rolling elements
- Diameter of rolling elements
- Spacing of rolling elements in cage
- Tolerances of rolling and sliding surfaces
- Chamfer of rolling elements
- Inner and outer screw hole diameter
- Inner and outer screw hole count
- Edge distance of screw holes
- Optional secondary screw holes

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/mod-bearing-angle-view-bw.png?raw=true)

# Testing
Rotation tests have been performed by hand on the modular bearing, demonstrating smooth motion. Testing with the WOLF actuator will be conducted soon.
Test video below (redirects to YouTube):

<div align="center">
      <a href="https://www.youtube.com/watch?v=DmYjyulmFeA">
     <img 
      src="https://img.youtube.com/vi/DmYjyulmFeA/maxresdefault.jpg" 
      alt="Test Video" 
      style="width:100%;">
      </a>
    </div>


# Bill of Materials
You will need the following:

Printed components:
- 1x inner ring
- 1x cage
- 1x outer ring, lower
- 1x outer ring, upper
- rolling elements (number will vary)

COTS components:
The size and quantity of commercial fasteners will vary depending on the configuration of the bearing. The following components are recommended for use with the modular bearing:
- roll pins (to secure the outer ring halves together)
- countersunk bolts, to attach the bearing

Tools:
- 3D printer
- Tweezers (to assist with bearing assembly)
- PTFE lubricant (Super-Lube) for bearing races and rolling elements

# Assembly Guide
## The bearing shown below is configured for the [WOLF actuator](https://github.com/Anthrobotics/wolf-actuator), however, the assembly procedure will apply to any modular bearing.
## Step 1: Place the inner ring inside of the lower half of the outer ring.

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/mod-bearing-wolf-step-1.png?raw=true)

## Step 2: Place the cage in between the inner ring and lower half of the outer ring.

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/mod-bearing-wolf-step-2.png?raw=true)

## Step 3: Insert the rollers into the cage. Alternate orientation of the rollers as shown below.

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/mod-bearing-wolf-step-3.png?raw=true)

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/mod-bearing-wolf-step-3(1).png?raw=true)

## Step 4: Apply PTFE lubricant (Super-Lube) to the rollers. Place the upper half of the outer ring on top of the lower.

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/mod-bearing-wolf-step-4.png?raw=true)

## Step 5: Secure the outer ring halves using 6 or 12 M3x10mm roll pins, by inserting them into the secondary holes of the rings.
### Note: It is advised to use the secondary holes to the left or right of the middle one, as that hole will typically be used to secure loads.

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/mod-bearing-wolf-step-5.png?raw=true)

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/mod-bearing-wolf-step-5(1).png?raw=true)

# Usage
The modular bearing can be integrated into a number of designs, including:
- robotic joints
- actuators
- motion platforms

# Contribute

Contributions from the community are welcomed! Please send us a message if you are interested in collaborating.

# License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

# Contact

If you have any questions or need support, please feel free to open an issue or contact us at:

Email: support@anthrobotics.ca

Website: [anthrobotics](https://anthrobotics.ca/)

Twitter: [@anthrobo](https://x.com/Anthrobo)

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/mod-bearing-top-view-bw.png?raw=true)
