# Hand landmarker and Face detection DEMOS

## Install requirements.txt
```bash
pip install -r requirements.txt
```


## Hand landmarker DEMO
---
### Download weights
```bash
mkdir -p hand_landmarker/weights && wget -q https://storage.googleapis.com/mediapipe-models/hand_landmarker/hand_landmarker/float16/1/hand_landmarker.task -O hand_landmarker/weights/hand_landmarker.task
```

### Run landmarker app
```python
python hand_landmarker/hang_landmarker_app.py
```

## Face detection DEMO
---

### Download weights
```bash
mkdir -p face_detection/weights && wget -q -O face_detection/weights/detector.tflite -q https://storage.googleapis.com/mediapipe-models/face_detector/blaze_face_short_range/float16/1/blaze_face_short_range.tflite
```

### Run face detection app
```python
python face_detection/face_detection_app.py
```