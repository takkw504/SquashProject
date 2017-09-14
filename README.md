# SquashProject


Video from testing of the system:  https://youtu.be/AyP5nZPOmzo

----------------------------------------------------------------



#Summary: 
----------------------------------------------------------------

Squash training application is a system created to help squash players with training exercises.  
The system projects a visible target on the back wall of the squash court and responds whenever the squash ball hits the projected target. 
Squash training application consists of ball tracking and graphical software, webcam, projector and a sound sensor module.

The graphical interface and the tracking software is written in C++ using SFML and OpenCV libraries. 
The sound sensor module consist of a Atmega328p, sparkfun sound sensor sen-12642 and a bluesmirf silver wrl-12577 the software is written in low level C.

-Version 1.0: Using two computers for the different tasks (ball tracking and graphical interface), communicating via tcp-ip. Sound sensor module using serial interface through usb. “Difficult to set up and use”

-Version 1.1 Changing detection method from colour detection to absolute difference.   

-Version 1.2 Adding a user friendly menu and auto ROI. Function for adding additional targets, removing targets and placing targets within the projected area.

-Version 1.3 Removing auto ROI  and replaced with advanced mousehandler function. 

-Version 1.4 Implemented threading to remove one computer. “The system now runs on one computer”.             
 
-Version 1.5 Removed usb connection from sound sensor module, replaced with  bluetooth connection.  

-Version 1.6 Added animated user guides and instructions to the program.   
