There are currently two jupyter notebooks in this repository.
1. Trad_Segmentation.ipynb : This notebook uses gray level thresholding to do feature segmentation on a scanning electron microscope(SEM) image. It takes png files as input and generates corresponding segmentation masks as svg files.
2. DeepLearning_IC-Segment : A U-net model is implemented for feature segmentation in this notebook. It uses SEM and its corresponding segmentation masks(.svg) as input for training.
3. A trained model can then be used to generate segmentation masks for new images.
4. sem0006.png is a sample SEM image which can be used for training.
