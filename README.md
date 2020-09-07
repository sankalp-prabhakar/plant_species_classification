# A primer on machine learning with image data for plant species classification

This tutorial is a primer on image data related machine learning. You will learn the basics of image data preprocessing &amp; data augmentation. You will then build classification models to classify plant species using traditional ML algorithm, CNN-based and pre-trained models. A brief summary of steps in this tutorial is listed below.

**Data:** Colored RGB images of healthy plant species was used from: https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color

### Steps in this tutorial

1. Load the dataset
   - Load healthy species
   
2. Eploratory data analysis
   - Plot randomly selected species
   
3. Initial data preprocessing
   - Resize images
   - Normalize image pixel values
   
4. Explore some image data preprocessing techniques
   - Change the color space
   - Gamma correct images
   - Histogram equalization technique (CLAHE)
   
5. Data augmentation
   - Generate & plot augmented image from a sample crop species
   - Generate augmented images in bulk
   
6. Generate labels

7. Shape and generate train/test data splits

8. Model training and evaluation
   - Using RandomForestClassifier
   - Plotting confusion matrix
   - Using CNNs
   
9. Using pretrained model - MobileNet
   - Use image generators with pretrained model
   - Model training and validation
   - Test model performance
