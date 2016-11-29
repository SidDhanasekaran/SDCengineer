# Self Driving Car Engineer
This Repo will contain all the instructions and the code snippets used by me (Siddarth Dhanasekaran) in the Udacity Self driving Car Engineer Nano degree. 

#Topics
1) Environment Setup

2) Lane Line detection using OpenCV

    - The Ipython notbeook (Sid_lanelines) has the code for lane detection of an image and a video
    
    - Test_images folder has the images and the videos used to test the code. 
    
    - I have used the following Pipeline for my Algorithm: 
    
        * Original Image to GrayScale : to make the image 1 channel
        
        * Grayscale to Canny Transform: to detect the edges
        
        * Canny to Gaussian Blur: To remove Gaussian Noise
        
        * Gaussian Blur to Region of interest: To limit the focus of the image to the lanes we are interested in
        
        * Region of interest to Hough lines: Identifies the Lane lines. 
        
        * Hough lines to Weighted image: Super imposes the Hough lines on the original image. 
        
       
    


