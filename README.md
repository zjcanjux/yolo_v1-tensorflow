## YOLO_V1_Tensorflow

YOLO_V1 writer by Tensorflow 

The folder including training and test phase.

### Installation

1. Clone yolo_v1_tensorflow repository
	```Shell
	$ git clone https://github.com/hizhangp/YOLO-V1_Tensorflow.git
    $ cd yolo_tensorflow
	```

2. Download Pascal VOC dataset, and create correct directories
	```Shell
	$ ./download_data.sh
	```

3. Download [YOLO_small](https://drive.google.com/file/d/0B5aC8pI-akZUNVFZMmhmcVRpbTA/view?usp=sharing)
weight file and put it in `data/weight`

4. Modify configuration in `yolo/config.py`

5. Training
	```Shell
	$ python train.py
	```

6. Test
	```Shell
	$ python test.py
	```

### Requirements
1. Tensorflow

2. OpenCV
