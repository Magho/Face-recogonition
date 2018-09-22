## Poject Description 
Build a face recognition system 

## Goals 
- Implement the triplet loss function
- Use a pretrained model to map face images into 128-dimensional encodings
- Use these encodings to perform face verification and face recognition

## Packages used 
- keras.models - Sequential-
- keras.layers - Conv2D, ZeroPadding2D, Activation, Input, concatenate -
- keras.models - Model -
- keras.layers.normalization - BatchNormalization -
- keras.layers.pooling - MaxPooling2D, AveragePooling2D -
- keras.layers.merge - Concatenate -
- keras.layers.core - Lambda, Flatten, Dense -
- keras.initializers - glorot_uniform -
- keras.engine.topology - Layer -
- keras - backend -
K.set_image_data_format('channels_first')
- cv2
- os
- numpy 
- pandas 
- tensorflow 
- fr_utils import *
- inception_blocks_v2 import *

## Used data set 
details inside the notebook