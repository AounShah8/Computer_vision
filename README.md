This project demonstrates how to load and process images using the OpenCV Python library. The main focus is on converting an image to grayscale and displaying both the original and grayscale versions of the image.

images.py Script
The script loads an image from the file system using OpenCV (cv2.imread).
It checks if the image has been successfully loaded, and if not, it prints an error message.
After successfully loading the image, it converts the image to grayscale using cv2.cvtColor.
The script then displays both the original and the grayscale versions of the image using cv2.imshow.
Finally, it waits for a key press and closes the image display windows (cv2.destroyAllWindows).
Images in the Images Folder
The Images folder contains three images of different bird species. These images are used as sample inputs for the images.py script:

