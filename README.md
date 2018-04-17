# PIC18F4620-ST7735R-GLCD
Library and samples for controlling a ST7735R GLCD using a PIC18F4620. Developed for usage in the course AER201 at the University of Toronto, in summer 2017.

## Contents
A graphical LCD (or GLCD) is able to display arbitrary images by addressing pixels with specific
color values. This folder contains a sample program that initializes a ST7735R-based GLCD, and demonstrates the 
fundamental graphics "function", drawing rectangles. Drawing pixels are also demonstrated as a 
special case of drawing rectangles.

The ST7735R may be implemented in a variety of displays. Among the most common are displays with a red pcb.
If you are using the V2.1 of the red GLCD PCB, use the file GLCD_PIC_V2.1.c. 
If you are using V1.1 of the red GLCD PCB, use the file GLCD_PIC_V1.1.c.

The difference between these two is just the adjustment of some screen offsets.