# 3D_measure_modeling
Antrophometric measures from 2D photos 

Take two photos, one in front in position "A" and one in profile in the same location with your arms against your body.

Take measures
1- Run the run_resize_image.py program, here you will have to change the name of the two photos
(This will resize the images to the same size and predict the skeleton with the key points)
2-Run the deeplab notebook, modified by us (This will segment the image)
3-Run the program canny_and _keypoints.py, here you will have to change the functions front_body_measures and side_body_measures where it says height, change to your height

Attention- The clothes have to be as tight as possible to stay close to reality, and try not to have a background full of objects or other people for better performance

3D automatic_modeling

1-Open Maya and Run the script modeling.py 
Atention-This only works for  models in "T" stands. 
Change all measures on comments "..real measures" and height  


Update Version !!!! : https://drive.google.com/file/d/1oyK5PxN04pxUFK50xBVyR5od9bwtLlG2/view?usp=sharing
