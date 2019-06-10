# -objectdetection-udetect
remember to subscribe to the fluffy snowman

to run the object detection python files you must first have python installed on ur terminal(bash/cmd).
make sure you have the 'pip' command installed
after these steps type in these commands into the terminal:
'pip3' can be replaced by 'pip' too 
pip3 install --upgrade tensorflow
pip3 install tensorflow
pip3 install numpy
pip3 install scipy
pip3 install opencv-python
pip3 install pillow
pip3 install matplotlib
pip3 install h5py
pip3 install keras
pip3 install https://github.com/OlafenwaMoses/ImageAI/releases/download/2.0.2/imageai-2.0.2-py3-none-any.whl
pip3 install imutils
pip3 install --user Cython
pip3 install --user contextlib2
pip3 install --user pillow
pip3 install --user lxml
pip3 install --user jupyter
pip3 install --user matplotlib


after installing all of these you should be good to go
download all the files in this repository(use git clone from terminal or just click clone or download on the top right).

open ur command line interface(cmd/terminal/bash)
path-to-the-folder is the location of the object detection folder that you just downloaded
type in:
cd /path-to-the-folder

to run the static image detection program, first put ur image in the object detection folder and then rename it to image.jpg
python static_image_detection.py

the output file will be named as imagenew.jpg




to run video object detection with higher accuracy(not live) then run:
python rttest.py

the output file will be named as 'camera_detected_video.avi'




to run the live object detection from the webcam use:
cd /path-to-the-folder
python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel

you must have all the files from this repository on your computer downloaded before running


have fun!
