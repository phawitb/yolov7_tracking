# yolov7_tracking  
## Install
#### 1.conda create -n yolov7_tracking python=3.9
#### 2.conda activate yolov7_tracking
#### 3.git clone https://github.com/phawitb/yolov7_tracking.git
#### 4.cd yolov7_tracking
#### 5.pip install -r requirements.txt
#### 6.python load_sources.py (wait a few minutes)
#### python detect_or_track.py --weights sources/yolov7.pt --no-trace --view-img --nosave --source sources/street.mp4 --show-fps
#### python detect_or_track.py --weights sources/yolov7.pt --no-trace --view-img  --source sources/street.mp4  
#### python detect_or_track.py --weights sources/yolov7.pt --no-trace --view-img --nosave --source sources/street.mp4 --show-fps --seed 2 --track --classes 0 1 --show-track --unique-track-color --nobbox --thickness 3

##### --seed > change color label
##### Check class > https://github.com/WongKinYiu/yolov7/blob/main/data/coco.yaml

## Reference
https://www.youtube.com/watch?v=K_OGcfXwskc   
https://github.com/haroonshakeel/yolov7-object-tracking  
https://github.com/WongKinYiu/yolov7  


#### ---------------------------------------------------------------------------
#### 1.conda create -n yolov7_tracking python=3.9
#### 2.conda activate yolov7_tracking
#### 3.git clone https://github.com/haroonshakeel/yolov7-object-tracking.git
#### 4.cd yolov7-object-tracking
#### 5.pip install -r requirements.txt
#### 6.Copy utils,models floder and yolov7.pt from git clone https://github.com/WongKinYiu/yolov7.git to dir yolov7-object-tracking

#### python detect_or_track.py --weights yolov7.pt --no-trace --view-img --nosave --source street.mp4
#### python detect_or_track.py --weights yolov7.pt --no-trace --view-img  --source street.mp4

