# car-number-plate-detection-and-recognition

Detecting car number plate and extracting text from it.

Read the image and do Preprocessing.
*  convert to gray scale
*  Do Cany Edge Detection
*  Find contours based on Edges

Initialize license Plate contour and x,y coordinates.
Find the contour with 4 potential corners and creat ROI around it. 
Removing Noise from the detected image, before sending to Tesseract.
 
Text recognition using pytesseract



