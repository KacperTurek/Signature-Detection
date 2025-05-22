
Signature Detection - v3 2024-11-11 5:00pm
==============================

This dataset was exported via roboflow.com on November 17, 2024 at 5:21 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 2819 images.
Signature are annotated in YOLOv8 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 5 versions of each source image:
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random rotation of between -10 and +10 degrees
* Random shear of between -4° to +4° horizontally and -3° to +3° vertically
* Random brigthness adjustment of between -8 and +8 percent
* Random exposure adjustment of between -13 and +13 percent
* Random Gaussian blur of between 0 and 1.1 pixels
* Salt and pepper noise was applied to 0.97 percent of pixels


