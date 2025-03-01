# Traffic Sign Classification (Comparing three classifiers)

## Dataset
Number of Instances : 15540
Number of Classes (types of Traffic Signs): 15

This dataset (in the folder `TrafficSignData`) contains 15540 images for 15 traffic signs, the image for each data is around 32X32 pixels, but not fixed. 
the images are saved in ppm files in different folders. Each folder represents one class of traffic
signs. In each folder, there is a csv file that includes the filenames in the folder, the width and height of each image, the Region of interest (x1,y1,x2,y2 illustrated in the image below) of each image, and the class ID or the output label.



## Introduction to the files
1. Three `SetParameters_x.py` files inlcude hyper-parameters tuning.
2. Training process of three classifiers included in `main_x.py`, and classifiers are saved in `clf_x.sav`.
3. Three `tester_x.py` files inlcude predictions on test dataset (splitted from the whole dataset).
