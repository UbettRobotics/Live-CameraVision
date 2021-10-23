# Live-CameraVision
Python program for use with EasyOpenCv and FIRST Tech Challenge.

## Use
This python program is designed to apply a HSV mask to a camera image that can be easily edited to see live feedback of how those parameters look. This easily enables the defining of those same parameters in a vision pipeline or other Java file on your robot. This program does not function with a FTC robot during a competition.

This program works well with the python IDLE environment at a minimum, and requires OpenCv and numpy to be installed. Running the program gives you the original image, an HSV conversion of the image, and the live mask output that is defined by trackbar values. The trackbars can be edited to get the best fit for your object.

## Utilization
The program uses a defined image in the same directory as the python file. You can manipulate the HSV min max values (of the mask), using the trackbars. For EasyOpenCv usage, you'll want to have fairly specific mask definitions, but various lighting conditions may affect the accuracy of the OpenCv analysis on the field. You should also keep in mind that the vision in competition will analyze live video frames, not a static image.

Two sample images have been included.
