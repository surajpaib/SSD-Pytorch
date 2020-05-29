# SSD-Pytorch

In this README, details about how to prepare the dataset and how to run the Quantitative object detection benchmark is described.

For the dataset processing using object detection in case of the "source" in the object-context approach, refer to the main README.md file.


Latest Pytorch implementation taken from:
https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Object-Detection



## Setting up the SSD-Pytorch.
First to run any object detection related processes, the checkpoint needs to be downloaded and saved in a conveninet location. The checkpoint can be downloaded from: https://drive.google.com/file/d/1bvJfF6r_zYl2xZEpYXxgb7jLQHFZ01Qe/view

Once this checkpoint is downloaded the ```detect.py``` script can be run to test if everything is in order. This script can be run with,
```
python detect.py --img_path <PATH_TO_TEST_IMAGE> --checkpoint <PATH_TO_CHECKPOINT>
```

Detailed usage,
```
usage: python detect.py [-h] [--img_path IMG_PATH] [--min_score MIN_SCORE] [--id ID]
                 [--checkpoint CHECKPOINT]

optional arguments:
  -h, --help            show this help message and exit
  --img_path IMG_PATH   Path to image to run the detection on
  --min_score MIN_SCORE
                        Minimum confidence score for prediction
  --id ID               Identifier to add to the image save name # TO BE IGNORED
  --checkpoint CHECKPOINT
                        Model checkpoint for eval
```                        

The detected image should be saved in this folder with a _detection suffix added to the original image path

## Running evaluation with SSD. 



## Testing sample detections with SSD


## Code Walkthrough






