# Classification of Road Features Using Transfer Learning and CNN

## Introduction
The study proposes a classification approach that utilizes transfer learning and convolutional neural networks (CNNs) to address the road feature classification problem.
The dataset contained 7616 images of roundabout, crosswalk, overpass, and intersection from the MLRSNet dataset and manually extracted satellite images from Malaysia using Google Earth Pro.
Transfer learning models such as ResNet50, MobileNetV2, VGG19 and InceptionV3 were also explored for road feature classification.
## Methodology
The dataset used in this study is primarily sourced from the [MLRSNet dataset](https://data.mendeley.com/datasets/7j9bv9vwsx/2) and additional satellite images of roundabout, intersection, crosswalk, and overpass in Malaysia were obtained by taking screenshots of those features using Google Earth Pro software.
A [custom CNN model](https://github.com/zl-gan/CDS521_Assignment2/blob/main/CNN.ipynb) is created in this study to perform classification of roundabout, crosswalk, intersection, and overpass.
Transfer learning models such as [ResNet50](https://github.com/zl-gan/CDS521_Assignment2/blob/main/ResNet50.ipynb), [MobileNetV2](https://github.com/zl-gan/CDS521_Assignment2/blob/main/MobileNetV2.ipynb), [VGG19](https://github.com/zl-gan/CDS521_Assignment2/blob/main/VGG19.ipynb) and [InceptionV3](https://github.com/zl-gan/CDS521_Assignment2/blob/main/InceptionV3.ipynb) are used to compare the accuracy with the CNN model developed.
## Results
The best performing model for road feature classification are ResNet50 and VGG-19 with an accuracy of 98.7132%.
## Conclusion
The study demonstrates the effectiveness of transfer learning and CNNs for the classification of road features.
The proposed approach offers a practical and efficient solution for accurate identification and categorization of road features, contributing to the advancement of intelligent transportation systems and enhancing overall road safety and efficiency.