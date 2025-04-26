# leaf-dataset
Training a pear leaf recognition and classification model requires feeding a large number of pear leaf images as sample images into the network architecture. We selected 6 representative varieties each from P.bretschneideri, P.pyrifolia, P.ussuriensis and P.communis, and selected 3 varieties from P.sinkiangensis. And in or-der to make the dataset more abundant, we also selected 6 varieties from P.hybrid. The leaf photos of pear varieties collected from the “National Pear and Apple Germplasm Resource Repository (Xingcheng)”. Images of pear leaves were captured under natural conditions using a mobile phone with a rear camera, the iPhone 13 model, with a reso-lution of 12MP. All camera optimizations such as HDR are disabled to avoid affecting model generalization. Place the phone at a distance of 30-40cm from the leaves for shooting. Collect images at different times of the day (8:00-18:00) to cover changes in natural lighting and ensure model robustness. The leaves selected were adult leaves, fully expanded, with no obvious signs of nutrient deficiencies, pathogen infection, or insect damage. In the images of dense foliage, there was leaf shading and leaf overlap. And when photographed under well-lit conditions, some leaves cast light and shadows from other leaves. Frontal im-ages of different leaves of 33 pear varieties were taken and 500 to 600 images were col-lected for each variety. The images were captured in JPG format with an image size of 3024 × 4032 pixels. In order to ensure the quality of the dataset, we manually filtered the images and finally a total of 17,656 pear leaf images were used to compose the pear leaf dataset. 

The pear leaf dataset was randomly divided into training set, validation set, and testing set in the ratio of 6:3:1 for training, validation, and prediction processes, respec-tively. The image data was manually labeled using the LabelImg tool. 


 
The leaf-dataset is composed of the "images" folder containing leaf images and the "labels" folder containing label files corresponding to leaf images.
﻿


# Data Availability Statement:
Given the substantial size of the dataset (59.83 GB), we provide two access options:

Baidu Netdisk: Download via https://pan.baidu.com/s/1k7_wAcWq8t-93ozX6IQpVQ (Extraction code: leaf)

Email Request: Contact the corresponding author (email: dongxingguangde@126.com) for a data copy

We guarantee response within 3 business days and will maintain data accessibility. Please notify us via email if any access issues occur.
