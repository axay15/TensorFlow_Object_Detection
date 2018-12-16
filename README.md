# TensorFlow_Object_Detection

TensorFlow Object Detection based on sentdex's tutorial.
Video link: https://www.youtube.com/watch?v=MyAOtvwTkT0&list=PLQVvvaa0QuDcNK5GeCQnxYnSSaar2tpku&index=2

Step 1: Install Dependencies

pip install tensorflow

pip install lxml

pip install protobuf

pip install opencv
(if opencv does not install by this method, then download the wheel file from - https://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv
and run - 

pip install downloaded_file.whl)




Step 2: Clone or Download the TensorFlow GitHub Repository
link - https://github.com/tensorflow/models.git

Step 3: Download releases for protobuf from 
https://github.com/google/protobuf/releases

Step 4: Compile the protoc libraries by running following command from the tensorflow/models/research/ directory :

protoc object_detection/protos/*.proto --python_out=.

if the above doesn't work, give the full path for the protoc.exe file you've downloaded in step 3 like so:

D:\TensorFlow_Object_Detection\protoc-3.6.1-win32\bin\protoc object_detection/protos/*.proto --python_out=.

Step 5: open jupyter notebook from the object_detection directory.
 Save a copy object_detection_tutorial.ipynb as a .py file in the  object_detection directory


Step 6: Open the .py file and make the changes as in object_detection_tutorial_webcam.ipynb

lines to add: 26, 27, 198, 201, 222-226

lines to comment/delete: 197, 199, 204, 219, 220


Sample Output: 







