# Crowd-detection-and-density-estimation-
This project detects and counts people in images using OpenCV, helping estimate crowd density for public safety, event management, and smart surveillance applications.
1. Purpose:

The purpose of this project is to develop a system that can automatically count the number of people in an image and estimate crowd density. This helps in:

* Managing large gatherings like concerts, rallies, or public events.
* Ensuring safety by monitoring crowd congestion.
* Enhancing surveillance and public security using computer vision.
* Supporting research in urban planning, smart cities, and social behavior analysis.

2. Technology Used:

This project leverages computer vision techniques and basic image processing to detect and count people. It uses:

* Grayscale conversion and histogram equalization for image enhancement.
* Background subtraction and thresholding to isolate foreground (people).
* Morphological operations to remove noise.
* Contour detection to locate and estimate people-like objects in the image.
* Filtering by area and aspect ratio to distinguish actual people from noise or objects.

3. Libraries Used:

The primary Python libraries used in this project are:

* OpenCV (cv2): For reading images, processing them, applying filters, and detecting contours.
* NumPy: For handling image matrices and performing morphological transformations.

4. Usage:

The program can be used in the following scenarios:

* Public Event Monitoring: Estimate the number of people at an event to manage safety and logistics.
* Smart Surveillance Systems: Automatically monitor crowd levels in CCTV footage.
* Retail Analytics: Estimate customer density inside stores or malls.
* Urban Management: Help local governments and planners analyze pedestrian flows.

How to Use:

1. Capture or input an image containing a crowd.
2. Run the script with the image path.
3. The system processes the image and outputs an estimate of the number of people.
