# counting-and-detecting-vehicles
In this project, I worked on detecting and counting vehicles in a given image or a video.

We will be using openCV for image processing and HAAR Cascade which is used for object detection. 

We can also create our own cutomized HAAR Cascade

## Scope

## Technology

## Steps
1. Loading the image from the internet.
2. Resizing the image and convert it into a numpy array. 
3. Converting image into Greyscale. 
4. Load the XML file which contains the HAAR Cascade. 
5. Using HAAR Cascade to detect the vehicle in the image.
6. Use the contours to create a rectangle around all the detected vehicles (cars).
7. Similarly we will perform these operations for another image for bus detection. 
8. Will use `bus_detection.xml` for bus detection.
9. We will also perform these operations on a video. 
10. Save the video with object detection.
