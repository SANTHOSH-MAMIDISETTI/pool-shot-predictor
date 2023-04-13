# pool-shot-predictor

Predicts Pool Shots in real time from s video source

I created a program that predicts the path of pool balls by using OpenCV and Numpy for color and shape detection. Different HSV filters are defined for each object, and coordinates of each object are used to calculate the likely ball path based on linear algebra. To account for the uncertainty in the cue’s exact location, the program calculates the most likely path among different possible outcomes. Contour analysis is used to find contours of the stick, cue, and ball in a specific frame. Mathematical calculations and projections are used to determine if a ball is inside one of the six holes on the table, which are drawn in green if present and red if not. Canny variables and Kernel size are adjusted to find contours of interest. The program accurately predicts the trajectory of pool balls by using a combination of color and shape detection, math calculations, and contour analysis.
