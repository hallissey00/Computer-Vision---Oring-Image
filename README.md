# Computer-Vision--Oring_Image
 to inspect a number of images of O-rings for defects. O-rings are rubber gaskets used for sealing the joint between two surfaces. It is possible that during the manufacturing process the O-ring may become flawed. required to inspect a number of images of O-rings for defects. O-rings are rubber gaskets used for sealing the joint between two surfaces. It is possible that during the manufacturing process the O-ring may become flawed.
Here is what you have to do:
•	Download the image set from moodle and have a look at the images. You will see the various flaws in the O-rings. The images are quite straightforward to segment with the O-ring on a uniform background.
•	Segment the image by analysing the image histogram to choose a threshold (automatically) and then perform the thresholding. Have a look at the binary image output and see if it needs any further processing to clean it up (e.g. binary morphology).
•	Implement connected componeent labeling  to extract the pixels belonging to the O-ring region which will be the largest foreground (possibly only) region.
One caveat here is that you cannot use opencv to analyse the image, you have to write your own image processing routines. You can use opencv functions to read in the images, display the images and annotate the output images with text or shapes etc.
•	Finding the threshold using the image histogram and performing the thresholding 
•	Performing the binary morphology to close any interior holes 
•	Implementing connected component labelling to extract the regions 
•	Overall program structure (measure the image processing time add it to the output image as a text annotation). 

