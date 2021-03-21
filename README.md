# imageprocessingfordropletsandbubbles
Calculation of bubble or droplet diameter after processing the image with python opencv package
You may adjust max and min threshold properties and pixel/mm values depending on your high-speed camera. It is written to calculate the bubble radius by 
fit a circle to the data. It creates bubble coordinates in mm and creates a photo to adjust the threshold parameters. 
You may run the code ./image from your terminal with python 2.7.1 version after installing the required packages. 
To clean the coordinates from the points I used the code from this website:
https://www.geeksforgeeks.org/how-to-check-if-a-given-point-lies-inside-a-polygon/


The image has been taken from the paper to process an image containing either a bubble or a droplet:

Mirsandi, H., Smit, W. J., Kong, G., Baltussen, M. W., Peters, E. A. J. F., & Kuipers, J. A. M. 
(2020). Influence of wetting conditions on bubble formation from a submerged orifice. 
Experiments in Fluids, 61(3), 1–18. https://doi.org/10.1007/s00348-020-2919-7

If contributions  are appreciated since I am very new in image processing.

