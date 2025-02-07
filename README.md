# PlantShield : GLCM and KNN Fusion in CNN for Robust Plant Disease Detection 
## Abstract : 
Plant diseases are a critical problem in modern agriculture, responsible for significant productivity losses of crops
and economic damages. This paper describes the PlantShield 
system that employs both texture-based as well as deep learning 
methods to enhance the robustness and precision of plant disease 
identification. The PlantVillage dataset, which has approximately 
54,000 photos of both healthy and damaged leaves from different 
plant species, serves as the foundation for the system. In this 
approach, textural properties like contrast and homogeneity are 
extracted using the Gray Level Co-occurrence Matrix, while deep 
visual features are extracted using CNN. This KNN method is used 
for fusing and classification of the features. The system would be 
supposed to offer a better performance when it comes to 
differentiation between subtle disease patterns through fusing 
low-level texture features with higher-level CNN features. 
Evaluation for the accuracy, recall, precision, and F1-score shows 
that the proposed solution by PlantShield is robust and reliable in 
early plant disease detection, promising its applic

## The PlantVillage Dataset

We use a publicly available and quite famous, the PlantVillage Dataset. The dataset was published by crowdAI during the ["PlantVillage Disease Classification Challenge"](https://www.crowdai.org/challenges/plantvillage-disease-classification-challenge). 

The dataset consists of about **54,305 images** of plant leaves collected under controlled environmental conditions. The plant images span the following **14 species**:

> **Apple, Blueberry, Cherry, Corn, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, and Tomato.**

The dataset contains a total of **38 classes** of plant disease and **1** class of background images listed below:
|                     |                      |                        |                          | 
| :---:               |    :----:            |          :---:         |         :---:            |  
| Apple Scab          | Apple Black Rot      | Apple Cedar Rust       | Apple Healthy            |
| Blueberry Healthy   | Cherry Healthy       | Cherry Powdery Mildew  | Corn Northern Leaf Blight|
|Corn Gray Leaf Spot  |Corn Common Rust      |Corn healthy            | Grape Black Rot          |     
|Grape Black Measles  | Grape Leaf Blight    | Grape Healthy          | Bell Pepper Healthy      |
| Orange Huanglongbing|Peach Bacterial Spot  | Peach Healthy          |Bell Pepper Bacterial Spot|
| Potato Early Blight | Potato Healthy       | Potato Late Blight     |Raspberry Healthy         |
| Soybean Healthy     | Squash Powdery Mildew| Strawberry Healthy     | Strawberry Leaf Scorch   |
|Tomato Bacterial Spot| Tomato Early Blight  | Tomato Late Blight     |Tomato Leaf Mold          |
|Tomato Septoria Leaf Spot| Tomato Two Spotted Spider Mite | Tomato Target Spot |Tomato Mosaic Virus |
|Tomato Yellow Leaf Curl Virus | Tomato Healthy      |    |    |

# Authors :
* Tarushi Sandeep Gupta
* Email id- tarushigupta03@gmail.com

* Shivani
* Email id- shivanisaini2173@gmail.com
