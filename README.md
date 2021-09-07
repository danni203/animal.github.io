# Animal
## Insall/libraries requirements
### Opencv4.2.0+CUDA for accelerating YOLOv3 process (see CUDA-OPENCV-INTALL.pdf)
[CUDA-OPENCV-INTALL](https://danni203.github.io/animal.github.io/CUDA-OPENCV-INTALL.pdf)
### Numpy
pip3 install numpy
### Scipy
pip3 install scipy
### PyEMD
pip3 install EMD-signal
### [YOLOv3](https://github.com/pjreddie/darknet)
[Dowload yolov3 weights](https://pjreddie.com/media/files/yolov3.weights)
## Code documents
[doc_code](https://danni203.github.io/animal.github.io/doc/animal.html)
## Code running tree

```bash
├── animal.py 
├── HR.py
├── UDP_server.py
├── videos // videos need to be processed
└── yolov3
    ├── coco.names
    ├── yolov3.cfg
    └── yolov3.weights
```
### Run the code
$ pyhon3 animal.py

