# object_detector
Detecting objects in a image and video using <b> YOLO framework </b>

<b>Steps to follow:- </b>
<p>
  1- Cloning this code https://github.com/pjreddie/darknet will bring darknet and all its related files into your system.
</p>
<p>
  2- Open the terminal in the darknet folder and type <b>make</b>.
</p>  
<p>
  3- Get the pre-trained weights for the model by typing : wget https://pjreddie.com/media/files/yolov3.weights .
</p>  
<p>
  4- Run the detector by typing : ./darknet detect cfg/yolov3.cfg yolov3.weights data/dog.jpg.
</p>
