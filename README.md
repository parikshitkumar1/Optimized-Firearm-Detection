---
# Firearm_Detector_v2

## Motivation
To detect firearms and enhance capabilities of cctv based security systems, in images, videos, and in real time.

## Requirements
Python 3.8 or above with all [requirements](requirements.txt) dependencies installed. To install run:
```python
$ pip3 install -r requirements.txt
```
### Downloads weights from here and put them in the root of this directory: 
### Google Drive Link: https://drive.google.com/file/d/13ZwaPrg_OdhZKCPIhWHAAxDc1tNE4lSj/view?usp=sharing
#### rename the weights to "yolov3.weights"


## To run for images
```python
$ python3 images.py
```
## To run for videos
```python
$ python3 video.py
```
## To run in real-time
```python
$ python3 realtime.py
```

## Image result:

<img src="https://user-images.githubusercontent.com/52780573/106359838-161aaf80-633b-11eb-975e-78ff7f5871cd.png" data-canonical-src="" width="800" height="500" />

## Video result:

<img src="https://user-images.githubusercontent.com/52780573/106359839-187d0980-633b-11eb-9d0a-a4260c30f383.gif" data-canonical-src="" width="800" height="500" />

## Real-time result:

#### (used phone as a webcam and made it detect firearms in random images on the internet and youtube videos)

<img src="https://user-images.githubusercontent.com/52780573/106359872-511ce300-633b-11eb-9c7a-b8024d2203c5.gif" data-canonical-src="" width="800" height="500" />

## Might Do
- [ ] Try out Yolo v4 and v5
----

