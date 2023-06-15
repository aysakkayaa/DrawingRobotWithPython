# DrawingRobotWithPython
The program that draws the shape / pattern that will be formed according to the direction, length, rotation angle and number of cycles entered by the user and
prints it to the screen. In order for the program to run correctly, first of all, make sure to add the following libraries if you are using pycharm or which compiler
you are using.

library: 
Pillow
Pillow-PIL	
customtkinter
darkdetect	
pip	
ply	
setuptools	
wheel	

The program has a simple interface within itself. The name of the txt file in which the format that will form the shape is written is entered in the left part of 
this interface. on the right, the visual state of the shape is displayed to the user when the drawing is finished. In order for this part to work, the program runs 
the ghostscript program in the background. If you have trouble with this, you can download ghostscript.exe from the internet. At the bottom of the interface, 
information is given about the commands that create the shape format. (error etc.)

L 36 [L 4 [F 100 R 90] R 10]

This is a sample shape command line. We can explain the pattern rule with an example as follows.
L stands for the loop and the number in front of it stands for the number of loops. The letter F indicates the straight direction the pen will draw and the length
of the number of lines in front of it. The letter R indicates the right turn and the number of turns in front of it. These loops and outgoing are read starting from
the innermost loop.
