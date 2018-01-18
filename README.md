# cs131-Computer-Vision-Foundations-and-Application
The Homework of cs131(http://vision.stanford.edu/teaching/cs131_fall1718/)
The code in here is my implementation of cs131 homework with python.
The assignments cover a wide range of topics in computer vision and should expose you to a broad range of concepts and applications.

Homework0 sets up the course with an introduction on how to use images in python and numpy. It covers basic linear algebra that would be helpful through the course.
    
HomeWork1 starts off the topics in computer vision by understanding concepts such as convolutions, linear systems and different kernels and how to design them to find certaions signals in images.(Please focus on convolutions and cross-correlation, Flip kernel or not)

Homework2 focus on edge detection, applying it to lane detection to aid self-driving cars. We implement canny edge detection method in this code. There are 4 steps about implementation of canny edge detection. 1. Noise reduction, 2. Compute intensity gradient and its magnitude, 3. Non-maximum suppression, 4. Double threshloding and tracing edges with hysteresis. About lane detection, we use hough transformation on canny edge detection image to detect straight line.
