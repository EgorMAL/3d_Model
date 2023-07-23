# 3d_Model
Draw  3d model from top view step by step images if you know stacking order of boxes

To launch application use main file. Create Model3d(imagesPath, boxQueue) object.
You need to pass the pathes to the folder with all images and csv file with box stacking order. The csv file needs the following columns: Id (unique box number), length, width, height. You can change pathes names in file const.py

To run application use run() method from Model3d
