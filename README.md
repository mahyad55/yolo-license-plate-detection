# License-plate Detection by YOLO

This repository contains a method to detect **Iranian vehicle license plates** as a representation of vehicle presence in an image. We have utilized **You Only Look Once version 3 (YOLO v.3)** to detect the license plates inside an input image. The method has the advantages of high accuracy and real-time performance, according to YOLO v.3 architecture. The presented system receives a series of vehicle images and produces the processed image with added bounding-boxes containing the vehicles' license plates. The flow of how we have trained and tested the application is published in a paper accessible from the citation section.

![Sample output of the system](Ali-Tourani-Sajjad-Soroori-Deep-Learning-LPD.png "Sample Output")

## Environment

- Python v.3
- You Only Look Once (YOLO) v.3
- A vehicle image dataset containing 3000+ samples (it will be available for academic usage soon)

## How to employ?

You can download the weight file from [this](https://drive.google.com/file/d/1vXjIoRWY0aIpYfhj3TnPUGdmJoHnWaOc/ "this") link.

Test on a single image:

```
python object_detection_yolo.py --image=bird.jpg
```

Test on a single video file:

```
python object_detection_yolo.py --video=cars.mp4
```

Test on the webcam:

```
python object_detection_yolo.py
```

### Contributers

<a href="https://github.com/alitourani/yolo-license-plate-detection/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=alitourani/yolo-license-plate-detection" />
</a>

## Citation

Please cite the following paper:

> S. Khazaee, A. Tourani, S. Soroori, A. Shahbahrami, and C. Y. Suen, “**A Real-time License-Plate Detection Method using a Deep Learning Approach**,” Lecture Notes in Computer Science (Springer, Cham), vol. 12068, pp. 425-438, 2020. ([link](https://doi.org/10.1007/978-3-030-59830-3_37 "link"))
