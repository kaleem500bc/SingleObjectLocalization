# SingleObjectLocalization
localize single object: trained only on birds images

## Model Architecture
Base Model: Pretrained InceptionV3 for feature extraction
Head Model: four layers of fully connected layers for bounding box regression

Only head model is trained while the base model weights are frozen.

## Dataset 
URL: https://github.com/ckczzj/Image-Object-Localization/archive/master.zip
Contains birds images and bounding boxes annotations
