# Lane-Detection

Lane detection in Indian roads, constitute a major challenge due to the presence of obstacles and uneven road conditions. Due to the variance in structure and non-uniformity of the path, lane detection algorithms require additional assistance to ensure accuracy and safety to make self-driving cars, a reality in India.

We using the following techniques for Lane Detection : 

###Color Thresholding

If you want to filter out any pixel that is not the color of the lanes. Lane lines are either white or yellow on roads. Color Thresholding is a perfect solution to discard objects of other colors.

###Hough Transform

The Hough Transform is a global method for finding straight lines (functions) hidden in larger amounts of other data. It is an important technique in image processing. For detecting lines in images, the image is first binarized using some form of thresholding and then the positive instances catalogued in an examples dataset.

###Canny Edge Detection

A Canny edge detector is a multi-step algorithm to detect the edges for any input image. It involves the below-mentioned steps to be followed while detecting edges ofan image :
- Removal of noise in input image using a Gaussian filter.
- Computing the derivative of Gaussian filter to calculate the gradient of image pixels to obtain magnitude along x and y dimension.
- Considering a group of neighbors for any curve in a direction perpendicular to the given edge, suppress the non-max edge contributor pixel points.
- Lastly, use the Hysteresis Thresholding method to preserve the pixels higher than the gradient magnitude and neglect the ones lower than the low threshold value.

###Clustering

Clustering is a method of unsupervised learning and is a common technique for statistical data analysis used in many fields. We can use clustering analysis to gain some valuable insights from our data by seeing what groups the data points fall into when we apply a clustering algorithm.
