# object-detection-opencv-python
OBJECT DETECTION-This model detects all the objects present in the given image.


 ## Libraries
  * opencv
  * numpy
  
`pip install numpy opencv-python`

 ## YOLO (You Only Look Once)
 
 Download the pre-trained YOLO v3 weights file from this [link](https://pjreddie.com/media/files/yolov3.weights) and place it in the current directory or you can directly download to the current directory in terminal using the following command
 
 `$ wget https://pjreddie.com/media/files/yolov3.weights`

When all the files are present in the directory,run project using cmd
 
 `$ python yolo.py --image example_03.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt'
