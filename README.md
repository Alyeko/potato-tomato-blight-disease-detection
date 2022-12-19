# potato-tomato-blight-disease-detection
In this repo are the notebooks and folder that can be used to reproduce results in our paper "Automatic Blight Disease Detection in Potato (Solanum tuberosum L.) and Tomato (Solanum lycopersicum, L. 1753) Plants using Deep Learning". 

## Files and folder present
## Notebooks
|Notebook name                    |Description |
|---------------------------------|------------|
|`1-potato-and-tomato-blight-disease-classification.ipynb`|Holds the code for the ResNet-9 model implementation, training and evaluation as well as saliency map creation|
|`2-using-the-already-trained-resnet9-model.ipynb`|Holds the code for evaluating an already trained ResNet-9 model (which can be found [here](https://www.kaggle.com/datasets/alyeko/pt-models))|
|`VGG-16 baseline model.ipynb`|Code for implementing and evaluating VGG-16 baseline model|
|`data augmentation for potato and tomato plant images.ipynb`|Has all the code used to augment the original images in order to increase the training set|

## Folder
In the folder `saliency_maps` are the six saliency maps found in the paper.
