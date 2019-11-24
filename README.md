# VGG-Face Transfer Learning
### Requirement
The following packages are needed for this project:
tensorflow 1.1X
pickle
opencv
### Usage
Please first download vgg_face weights from http://www.robots.ox.ac.uk/~vgg/software/vgg_face/ and the dataset from https://s3.amazonaws.com/matroid-web/datasets/agegender_cleaned.tar.gz
After downing the dataset, please use pack_data.py to pack the image into binary pickle files. It will give you three files including train.pickle, val.pickle and test.pickle£¬where train.pickle and val.pickle are from "\data\agegender_cleaned\combined\aligned" and test.pickle is from "\data\agegender_cleaned\combined\valid". Then use train.py to train the model. I wrote step by step instructions and included all the results in the jupyter notebook, **Training.ipynb**, so please refer to that for more details.