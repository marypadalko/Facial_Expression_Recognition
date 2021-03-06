# Facial Expression Recognition

In collaboration with drorrosen (https://github.com/drorrosen)


![image](https://drive.google.com/uc?export=view&id=1vjntSNkaeuyZOT1s2c_7iY8GKFTVWep2)

# The steps:

![image](https://drive.google.com/uc?export=view&id=147Ow9pY75ELQKNkW6PFsWr49-lf5taj5)

# Preparing the data, visualization, augmentation and balancing:

![image](https://drive.google.com/uc?export=view&id=1Tc_httT7uXYTTYaIHbQpv6588BfESUdI)

# Augmentation of train data:

The original train data contained from 400 to over 7K of images for each label, augmentation ads <= 4000 images per label, the amount of generated and added pictures depend on label. For example, minority class grew up to 2292 images.

![image](https://drive.google.com/uc?export=view&id=1groGyH0AM4caDUbFX3VRo5eiLVQbg3fk)

# Selecting balanced subset of augmented train set
The next goal is to select images to get balanced (or almost balanced) data. We decided to take 5K of images per each label. All labels we presented by 5000 of images except most rare label 1 with almost 2300 images

![image](https://drive.google.com/uc?export=view&id=151rOz81xY5jcnW3udZf4Pkdhpu6QALj2)

# Running a few ML models on the prepared data:

RFC and XGBoost gave up to 41% accuracy on both test sets

![image](https://drive.google.com/uc?export=view&id=1LFwmIzFpPljpjcwIZWI4HU7kHMdJ77Ab)

# And, finally, Neural Nets:

Implemented CNNs and used VGG16 with some changes (MaxPooling, BatchNorm, Dropout). All models were trained using ReduceLROnPlateu, best result is 63.34 on Public Test and 63% on Private Test.


![image](https://drive.google.com/uc?export=view&id=1pquiOlMWezTFCxXZJOuIYAmzeeVFAHus)


The results can be compared with the leaderboard from Kaggle competition here: https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/leaderboard (Probably, it would be top-10)


# A CNN model was used to predict facial expressions from the webcam

![image](https://drive.google.com/uc?export=view&id=1dFoeGt9C5i0Ir7x2-7X5AETKjhskkA45)



Credits: thanks Slidesgo, Freepik, Flaticon for design
