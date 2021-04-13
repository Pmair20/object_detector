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
<b>Output Image Generated<b><br />
</p>
  <img align="left" alt="Predictions Image" src="https://github.com/Pmair20/object_detector/blob/main/predictions.jpg" /><br />
</p>

<b>Note:- <b><br />
<p>
  The detection weights and data being used has been used from : https://pjreddie.com/darknet/yolo/ 
  This is simply a demonstration of object detection on an image.
  It is possible to run this on camera input as well as video.
</p>  
