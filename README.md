# Object-TrackingwithYoloV5
```
git clone https://github.com/ImtiazUlHassan/Object-TrackingwithYoloV5.git

cd Object-TrackingwithYoloV5

python3 -m venv Yolov5env
```
# Activate the newly created environment (for Unix/Linux)
```
source Yolov5env/bin/activate

git clone https://github.com/ultralytics/yolov5  # clone

mv object-Tracking.py objectdetection.ipynb yolov5/


pip install -r requirements.txt  # install

cd yolov5



#for object detection + object tracking
python object-Tracking.py --weights yolov5s.pt --source "path to the video"

```



