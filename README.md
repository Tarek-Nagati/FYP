# FYP
Final Year Project

This is a code for the diagnosis of Diabetic retinopathy. In this project, is developed a machine learning and deep learning algorithms, which will detect diabetic retinopathy by scanning retina images. 
The dataset in this project is a collection of retina’s images for both eyes right and left. The dataset has been taken from Kaggle website (publicly published) size 7GB includes 35,108 images, provided by (ilovescience account, 2019). It consist of two folders and two files, one folder resized_train with 35,127 raw images and the relative trainLabels.csv which includes two columns ‘image and level’, and the other folder resized_train_cropped with 35,108 cropped images and removed bad images, with the relative trainLabels_cropped.csv file for training the data.  
Every image has its own label (for instance, 10_left, the number of image and which eye) and value (for instance, 0, 1, 2, 3 or 4) which indicates if the eye has a disease or not and the severity of the disease. The images sorted into 5 categories in a scale from 0 to 4, below shows the description of the values.

0	No Disease, 
1	Mild,
2	Moderate,
3	Severe,
4	Proliferative Diabetic Retinopathy.

The web link for the dataset is --> https://www.kaggle.com/tanlikesmath/diabetic-retinopathy-resized
