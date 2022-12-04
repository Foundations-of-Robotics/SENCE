# SENCE
Repository for the System for Enhanced Navigation of Constrained Enviroments (SENCE) robotic platform featured in the ACRA 2022 article Design of a Novel Multi-gait Quadruped.

This contains all required CAD and firmware files to build the hardware, simulate the system and run preprogrammed gaits. We hope other researchers find this system to be a valuable learning platform.

sence_paper contains the required ros package holding all the sence configuration information including micro controller communication and simulation execution.

sence_build contains all CAD files used to produce the system in two seperate formats. Original Parts (Fusion) contains all fusion source files and a full body project fusion f3z file. Original Parts (3MF Conversion) contains conversions of the leg and chassis files from fusion into 3MF for compatability but looses all joint and object material data (should only be used for printing).

Created by Dylan Morley, David Hinwood and Damith Herath at the University of Canberra Collaborative Robotics Lab.
