Hi;)
I present to you the program for creating contours from video from your webcam.
It based on Topological structural analysis(Suzuki et al.,1985)
For the beginnig, we use Edge Detector Canny to get binary image.
We calculate the threshold for it in three way.
First way, we use the arithmical mean of the intensity of a grayscale image to estimate the threshhold like: 
	low_threshold=0.66*mean and high_threshold=1.33*mean.
Second way, we plot a histogram of the intensity and employ its median value:
	low_threshold=0.66*median and high_threshold=1.33*median.
You can choose the way.
Third, we used a constant value, for example 70, and we calculate thresholds as shown above.
In the end, we find and draw the contours in real time.
This program was made for fun.
Perhaps you can find it useful.
---------------------------------
Best wishes!
Dmitry Utev.	
