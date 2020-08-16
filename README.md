# Facial_Expression_Recognition



![image](https://drive.google.com/uc?export=view&id=1pxyxyWiPRlpQuAmYSfbzDteNIt7qKg_V)

The steps:

![image](https://drive.google.com/uc?export=view&id=1vjntSNkaeuyZOT1s2c_7iY8GKFTVWep2)

Preparing the data, visualization, augmentation and balancing:

![image](https://drive.google.com/uc?export=view&id=1Tc_httT7uXYTTYaIHbQpv6588BfESUdI)

Augmentation of train data:

The original train data contained from 400 to over 7K of images for each label, augmentation ads <= 4000 images per label, the amount of generated and added pictures depend on label. For example, minority class grew up to 2292 images.

![image](https://drive.google.com/uc?export=view&id=1groGyH0AM4caDUbFX3VRo5eiLVQbg3fk)

The next goal is to select images to get balanced (or almost balanced) data. We decided to take 5K of images per each label. All labels we presented by 5000 of images except most rare label 1 with almost 2300 images

![image](https://drive.google.com/uc?export=view&id=151rOz81xY5jcnW3udZf4Pkdhpu6QALj2)

The next step is to run a few ML models on prepared data:

![image](https://drive.google.com/uc?export=view&id=1LFwmIzFpPljpjcwIZWI4HU7kHMdJ77Ab)

And, finally, Neural Nets:

![image](https://drive.google.com/uc?export=view&id=1MCOjNgwkCy1L4Dbz7BUABIiwkRnHd0nt)
