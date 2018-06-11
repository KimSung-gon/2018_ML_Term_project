# 2018_ML_Term_project

I tried to track the rc_car on the webcam attached on TX2 board.

I used darknet yolo network.
Darknet link : https://github.com/pjreddie/darknet                                                                             
Using Yolo tiny v2 network to make real time system.
It about 17fps close to real time(20fps).
The Yolo tiny v2 network has 16 layer to make fast.
And I used Yolo_mark to mark the location of rc_car.
Yolo_mark link : https://github.com/AlexeyAB/Yolo_mark

usage:
./darknet detector demo data/obj.data yolov2-tiny-one-class.cfg yolov2-tiny-one-class.backup -c 1 -thresh .3
