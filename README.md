# vod-converter
Visual Object Dataset Converter. Requires Python 3.6

Kitti object tracking to VOC


1. Git clone this repository
2. $ cd vod-converter
3. $ sudo apt install python3.6-venv              <- get python 3.6 virtual environment
4. $ virtualenv --python=python3.6 venv36
5. $ source venv36/bin/activate
6. $ python3 -v                                   <- verify version
7. $ pip install -r requirements.txt
8. Download the kitti object tracking data set and training labels http://www.cvlibs.net/datasets/kitti/eval_tracking.php
9. Extract the files
10. $ python3.6 vod_converter/main.py --from kitti-tracking --from-path /home/hc/Downloads/kitti/training --to voc --to-path /home/hc/Downloads/kitti_voc
- Note: traning file path should containt the image_02, label_02, and train.txt



Reference: https://github.com/umautobots/vod-converter
