# annotate-faces

A very simple graphical facial landmark annotation tool using Matplotlib and OpenCV.

This version helps you manually annotate a bounding box and 5 points: left eye center, right eye center, nose tip, 
leftmost mouth point, rightmost mouth point. 
You can run the script for a single image or multiple images in a directory. Points are output to stdout in csv format,
but you will probably want to redirect it to a file.
