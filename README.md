# Mango Leaf Disease Classification using TensorFlow
This notebook uses a dataset of 4000 images of mango leaves captured from four mango orchards in Bangladesh, which include seven different diseases and a healthy category. The images are in JPG format and have a resolution of 240x320 pixels. The dataset includes 1800 distinct leaves and 2200 images that were prepared by zooming and rotating when necessary. The images were taken from Kaggle in https://www.kaggle.com/datasets/aryashah2k/mango-leaf-disease-dataset?select=Sooty+Mould.

## Data Description:
- Type of data: 240x320 mango leaf images.
- Data format: JPG.
- Number of images: 4000 images.
- Number of distinct leaves: 1800
- Diseases considered: Anthracnose, Bacterial Canker, Cutting Weevil, Die Back, Gall Midge, Powdery Mildew, and Sooty Mould.
- Number of classes: Eight (including the healthy category).
- Distribution of instances: Each of the eight categories contains 500 images.
- How data is acquired: Captured from mango trees through the mobile phone camera.
- Data source locations: Four mango orchards of Bangladesh, namely Sher-e-Bangla Agricultural University orchard, Jahangir Nagar University orchard, Udaypur village mango orchard, and Itakhola village mango orchard.
 
## Objective
The main objective of this notebook is to classify mango leaves into one of the eight categories: Anthracnose, Bacterial Canker, Cutting Weevil, Die Back, Gall Midge, Healthy, Powdery Mildew, and Sooty Mould, using TensorFlow. The model developed in this notebook can be used to distinguish healthy and diseased leaves (two-class prediction) as well as for differentiating among various diseases (multi-class prediction).

## Methodology
The methodology used in this notebook involves the following steps:

Loading the dataset and preprocessing the images
Splitting the dataset into training, validation, and testing sets
Building a Convolutional Neural Network (CNN) model using TensorFlow
Training the model using the training set and validating it using the validation set
Evaluating the model using the testing set

## Conclusion
In this notebook, we have demonstrated how to use TensorFlow to classify mango leaves into different categories of diseases. The trained model achieved good accuracy on the testing set, indicating that it can be used for practical applications such as identifying diseased mango leaves in the field.

## Contribution
Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue in the repository or submit a pull request.
a pull request.

