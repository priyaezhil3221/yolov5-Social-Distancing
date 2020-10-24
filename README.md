# Social-Distancing-using-YOLOv5



### Detecting people and were classified as high, moderate and normaL based on their distance to other people :mask:


The original [YOLOv5](https://github.com/ultralytics/yolov5 "YOLOv5") model was used to detect people. Thereafter the people were classified as "*High*" , "*Moderate*" and "*Normal*" based on their distance from one another.


---

## Requirements


Python 3.7 or later with all `requirements.txt` dependencies installed, including `torch >= 1.5`. To install run:
```bash
$ pip install -U -r requirements.txt
```


---

## Usage


Run on a single video file


```bash
$ python detect.py --source ./inference/videos/videofile.mp4
```


Run on all video files inside a folder


```bash
$ python detect.py --source ./inference/videos/
```


---
## Output

![](output.gif)
