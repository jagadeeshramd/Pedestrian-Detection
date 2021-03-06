# Pedestrian-Detection
Developed under Verzeo's Artificial Intelligence Internship program. A simple pedestrian detection program that makes use of YOLOv3 model and OpenCV for image recognition

# To run
Prerequisites: NumPy, OpenCv, imutils.
If these libraries are not pre-installed, run the following commands on the terminal.

`pip install numpy`
`pip install opencv-python`
`pip install imutils`

1. Download the repository 
2. Download the yolov3.weights file from [here](https://drive.google.com/file/d/1ifZ4WnXYOKHwSiKS9XfVuBJtaeZfNdIF/view?usp=sharing) and add the same to the yolo-coco folder. (I couldn't upload it here as the file is too big.)
3. Type the following in the command prompt.

`python pedestrian_detection.py --image images --yolo yolo-coco`

More input images can be given by placing the required images in the images folder with naming pedestrian_imageX.jpg where X is an integer that is not already used. The corresponding outputX.jpg image can be found in the outputs folder.
