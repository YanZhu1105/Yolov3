# Implementation of YOLO_v3 from Scratch
This implementation follows Ayoosh's guide on YOLO_v3. Full tutorial is [here](https://blog.paperspace.com/how-to-implement-a-yolo-object-detector-in-pytorch/).

## Usage
Run detector.py with the following parameters:
- image_or_video (input type, default = image)
- images (input directory)
- other custom parameters

Example:
```python
python detector.py --images dog-cycle-car.png --image_or_video image
```

## Some Info
This implementation uses the original [yolov3](https://github.com/ultralytics/yolov3/blob/master/cfg/yolov3.cfg) configuration. Input images are resized to 416 * 416.
With enough GPU resource, you can change this setting to be bigger.

## Sample Output
![dog-cycle-car](https://github.com/YanZhu1105/Yolov3/blob/master/dog-cycle-car.png)
