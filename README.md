# CARTOONIFYING-AN-IMAGE-USING-OpenCV-AND-ML-
Cartoons are illustrations of characters that can be imaginary or are based on a personality.
They are semi-realistic or non realistic ,which are popular nowadays to depict  a situation or a happening in a funny ,satirical way.

Earlier ,cartoonists used to draw these cartoons by hand and when anime started catching the light ,it became difficult for them to attract each movie frame  by hand ,which took a lot of time and was not reversible if met with a mistake.

With increasing technology ,numerous software came into the market to digitally  draw the  illustrations ,thus reducing human effort and were more efficient than being drawn by artists.
Automation technology  is booming nowadays. Human effort is reduced to the minimum with  a  set of programs  doing our job for us , animation technology has taken a considerable leap . This project will converts regular camera clicked images into cartoonized form.
We are living in an era of making the impossible things to be the mostly possible things.
Imagine yourself as a person having no knowledge on drawings but willing to gift a drawing 
To someone .In that case what anyone think of is how fortune it will be if a drawing that you 
wish  comes out within much less time and with out much efforts. Yes! One such a thing is 
obtaining  a cartoon image . Cartoonifying an image is a computer vision application done 
using  python language . This project is such a way  that the user can get cartoonized  image 
for  whatever image input he gives. The user can also save the output cartoonized image .
Unlike many other softwares the resulting image will be saved in the same path of user’s 
input   reducing the mess to search for it again .Also the output for the given input will be 
shown  showing variations in the process to obtain  cartoon.
                                                                    

Image processing is widely processed in the medical field such as in the MRI/ET scans. The 
Amount of research in the image processing has helped to acquire early detection of  
tumors.  They are playing vital role in the field of biology . The recent  technology of 
fingerprint  unlock, face  detection unlock has resulted in the developing  an efficient 
security. The techniques installed in the social media platforms like facebook,Instagram 
apprehending  to its success with enhanced user experience. The  basic concept in this 
project is  to apply some conversions and filters  to obtain a beautiful cartoon image.
Cartoonifying an image requires adding an effect to the image .
=========================================================================================================================================================
METHODOLOGY:
-------------------
-----------------
Python  has lot  of libraries. One such library is OpenCV. It  is  a cross platform library used 
For  computer vision.

Step 1: Import the required modules
•	CV2: Use OpenCV for image processing.
•	easygui: Used to open a file box. It allows to select any file from our system.
•	Numpy: Images are stored and processed as numbers. These are taken as arrays.
•	Imageio: Used to read file which is chosen by filebox using a path.
•	Matplotlib:This library used for  visualization and plotting .It is imported to form plot 
Of images.
•	OS: for OS interaction.Used to read the path and save images to that path.

Step 2 : Building a file box to chose particular file.

Step 3: How is an image stored – We will convert our image into numpy array.

Step 4: Transforming image into grayscale 
•	cvtColor(image,flag) is a method in cv2 which is used to transform an image into the 

colour-space mentioned as flag. We use BGR2GRAY flag. This returns image in 

grayscale .


Step5: Smoothening a grayscale image 
•	To smoothen an image  simply apply blur effect. This is done using medianBlur() function.


Step 6: Retrieving the edges of an image
•	Cartoon effects has 2 specialities : Highlighted Edges , Smooth colors
•	Retrieve the edges and highlight them .This is attained by the adaptive thresholding technique.
Step7: Color quantization of image using k -means clustering algorithm.

Step 8: Preparing a mask image

Step 9: Giving a cartoon  effect.

Step10: Plotting all the transitions together

Step11: Functionality of save button

Step 12: Making the main window

Step13 : Making the cartoonify button in  the main window

Step14: Making a save button in main window

Step15: Main function to build the tkinter window
