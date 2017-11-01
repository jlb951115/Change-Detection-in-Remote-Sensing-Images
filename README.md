## Change Detection in Remote Sensing


#### Project Organization

- ```main```: Pipeline for training and evaluation
- ```config```: Model config and file paths
- ```checkpoint```: MXNet checkpoint files
- ```data```:  Rawdata and temporal data
- ```Pretrain_model```: pretrained model file
- ```model```:  MXNet Symbols of VGG16, Resnet
- ```utils.preprocessing```: Utility function for preprocessing, such as PCA, Rescaling.
- ```utils.io```: Utility function for I/O
- ```utils.filter```: Weighted median filter
- ```utils.label_data```: A handy tool for labeling data manually.

#### Requirements
- Apache MXNet 1.0
- python 2.7