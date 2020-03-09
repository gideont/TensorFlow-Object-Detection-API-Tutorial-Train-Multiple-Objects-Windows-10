# Quick Start Guide

Make sure you've followed the Tensorflow Object Detection API installation guide:
 * https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md

To start inference using images in the test_images/ folder:
```console
$ python3 detect_single_image.py 
```
The above do inference with a single image then save the image with boxes. Good example for docker use/test.

To start inferencing using multiple images in the test_images folder.  Result images will pop up but you'll need access to X(which most docker doesn't have)
```console
$ python3 detect_multiple_images.py 
```

To start inference using webcam(require access to webcam and X display:
```console
$ python3 detect_webcam.py
```

