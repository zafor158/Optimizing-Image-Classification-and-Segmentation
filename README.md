# Optimizing Image Classification and Segmentation: A Comparative Study of Deep Learning and Machine Learning Models

🏆 Award-Winning Research

This project has been recognized with the Best Paper Award at the International Conference on Data Mining and Information Security (ICDMIS) 2024. The research explores and evaluates the performance of various deep learning and machine learning models in image classification and segmentation tasks, showcasing innovative methodologies and achieving state-of-the-art results

# Certificate

![Best Paper - Track 9_2 (1)_page-0001](https://github.com/user-attachments/assets/dfdffbdd-5a5c-4cc4-a1ec-dd718999aa4c)



# Abstract:
Skin diseases pose significant challenges in identification and treatment due to subjective assessments and the unreliability of traditional diagnostic tests. This project aims to improve the precision and effectiveness of skin disease classification through the application of deep learning and machine learning algorithms.

The study evaluates a range of models, including:

* Deep Learning Models: Custom CNN, ResNet101V2, VGG16, InceptionResNetV2.
* Machine Learning Techniques: Decision Trees, Logistic Regression, Random Forests.
* Image Segmentation: YOLOv8 for precise segmentation.

# Methodology Diagram:

![system architecture](https://github.com/user-attachments/assets/6e7b200a-75b5-4907-8b97-8dd12c308c6d)

#  Dataset 

The dataset used in this research is sourced from the RoboFlow platform and Kaggle, titled “Skin Cancer ISIC: The International Skin Imaging Collaboration.” This dataset is specifically designed for skin disease classification and segmentation tasks.

## Skin Disease Classes and Common Signs

| **Class Type**                        | **Common Signs**                                                                                         |
|---------------------------------------|---------------------------------------------------------------------------------------------------------|
| **Melanoma**                          | - Itching or tenderness<br>- Changes in texture<br>- Bleeding or oozing<br>- Redness or swelling<br>- Satellite moles<br>- Dark streaks under nails<br>- Lesions on mucous membranes<br>- Rapidly growing lumps |
| **Actinic Keratosis (Solar Keratosis)**| - Rough, scaly patch on the skin                                                                        |
| **Dermatofibroma**                    | - Firm, raised nodule                                                                                  |
| **Melanocytic Nevi (Common Moles)**   | - Uniformly colored and shaped spot                                                                    |
| **Vascular Lesions (Vascular Tumors)**| - Red or purple spots or bumps                                                                         |
| **Basal Cell Carcinoma**              | - Pearly or waxy bump on the skin                                                                      |
| **Benign Keratosis-like Lesions**<br>(Seborrheic Keratosis) | - Waxy, “stuck-on” appearance                                                                          |


## Skin Disease Class Distribution

| **Class Type**                        | **Count** |
|---------------------------------------|-----------|
| **Melanoma**                          | 1,113     |
| **Actinic Keratosis (Solar Keratosis)**| 327       |
| **Dermatofibroma**                    | 115       |
| **Melanocytic Nevi (Common Moles)**   | 6,705     |
| **Vascular Lesions (Vascular Tumors)**| 142       |
| **Basal Cell Carcinoma**              | 514       |
| **Benign Keratosis-like Lesions**<br>(Seborrheic Keratosis) | 1,099     |
| **Total**                             | 10,015    |


# Data set images:
![image](https://github.com/user-attachments/assets/9bbbe45d-a2cc-43be-94a0-1627be75a12a)

# Model Description

1. Custom CNN (Convolutional Neural Network)
Custom CNN is a tailored neural network architecture designed specifically for the project’s requirements. It leverages:

* Convolutional layers to automatically extract spatial features from images.
* Pooling layers for dimensionality reduction, improving computational efficiency.
* Fully connected layers to classify extracted features into corresponding categories.
* Custom CNNs are optimized for the dataset and task at hand, offering flexibility and simplicity for specific applications like skin disease classification.

![Custom CNN](https://github.com/user-attachments/assets/f886a8bf-a0c9-4aec-9f14-c4d3dd035e6a)

2. DenseNet201
DenseNet201 features a unique architecture designed to address the limitations of traditional deep learning models. The model employs a dense connectivity pattern, where:

* Each layer is directly connected to every other subsequent layer through a feed-forward mechanism.
* Layers reuse features by concatenating their outputs, improving efficiency and mitigating issues like vanishing gradients.
* DenseNet201 is highly effective for tasks requiring deep networks while maintaining computational efficiency.

![Densenet201](https://github.com/user-attachments/assets/728a5ade-caf9-40db-941c-5c42be68d78a)

3. ResNet101V2
ResNet101V2 is an improved version of the Residual Network (ResNet) and incorporates:

* Pre-activation residual blocks to enhance gradient flow and training efficiency.
* Batch normalization (BN) and ReLU activation applied before convolution layers.
* This architecture ensures smoother training and higher performance in deep networks.

 ![image](https://github.com/user-attachments/assets/e341efe3-4008-4294-b8f4-791dbbdd0e8e)

4. InceptionResNetV2
InceptionResNetV2 combines the strengths of Inception modules and residual connections to:

* Learn a hierarchy of abstract features through convolution, pooling, and non-linear activations.
* Enhance performance and efficiency, making it suitable for state-of-the-art computer vision tasks.
* Operate robustly across various applications due to its innovative combination of Inception and ResNet features.

![InceptionResnetv2 diagram](https://github.com/user-attachments/assets/4f9edcba-2de7-48a0-919e-5144ecf3a4af)


5. Logistic Regression
Logistic regression is a fundamental machine learning algorithm primarily used for:

* Binary classification problems, mapping the relationship between input features and the probability of an outcome.
* Utilizing the logistic function to map the output of a linear combination of features to probabilities ranging between 0 and 1.

![Logistic regression](https://github.com/user-attachments/assets/d071637a-b4f4-4c30-bdc6-7c27199ed140)


5. Random Forest
Random Forest is a popular ensemble learning technique for classification and regression tasks:

* Builds multiple decision trees during training, each trained on random subsets of data and features.
* Reduces overfitting and increases robustness by introducing randomization in tree-building.
* Combines predictions from all trees to deliver more accurate and reliable results.

![Random Forest](https://github.com/user-attachments/assets/64f78e7a-8a6d-403c-965b-1acc5067739b)

6. Decision Tree
A Decision Tree is a straightforward yet powerful machine learning algorithm:

* Recursively divides the feature space into smaller parts based on feature values.
* Uses metrics like information gain or Gini impurity to determine the optimal splits.
* Efficiently handles classification and regression tasks by creating interpretable tree-like models.

![Decision tree](https://github.com/user-attachments/assets/857747a4-dae7-4112-8915-12417a8ee201)

7. YOLOv8x
YOLOv8x, an enhanced version of YOLOv8, excels in real-time object detection and segmentation:

* Integrates the C2f module to replace the CSP layer, improving contextual feature discovery.
* Incorporates an anchorless approach with a splitting head for better object detection, box integration, and similarity matching.
* This innovative adaptation builds on Faster R-CNN principles to deliver cutting-edge performance in object detection tasks.

![Yollov8x diagram](https://github.com/user-attachments/assets/e55543b8-ce11-4dbd-9a0c-3b78c41a2618)

# Proposed Model:
VGG16 Model
The core of the proposed approach is a modified VGG16 architecture, which has been fine-tuned for skin disease classification. The model architecture includes the following layers:

* Input Layer: Accepts preprocessed images for processing.
* Conv2D Layers: Extracts features by detecting patterns like edges, textures, and complex structures using convolutional filters.
* Batch Normalization Layers: Normalizes activations from the preceding layer, enhancing training stability and convergence speed.
* MaxPooling2D Layers: Downsamples the spatial dimensions of feature maps, reducing computational overhead while preserving dominant features.
* Flatten Layer: Converts 2D feature maps into 1D feature vectors for subsequent dense layers.
* Dense Layer: Fully connected layer that combines extracted features for accurate classification.
* Output Layer: Produces the final predictions, corresponding to the skin disease classes.
The modifications and optimizations to the VGG16 architecture make it particularly effective for the complex task of skin disease classification.

![VGG16_A](https://github.com/user-attachments/assets/2ef6b98b-b68e-4705-b096-925c8d15263c)


## Model Training and Performance Comparison

### **Deep Learning Models: Training and Validation Results**

| **Model**           | **Training Accuracy** | **Training Loss** | **Validation Accuracy** | **Validation Loss** |
|----------------------|-----------------------|-------------------|--------------------------|----------------------|
| **Custom CNN**       | 0.7703               | 0.5080            | 0.5503                  | 1.7417              |
| **DenseNet201**      | 0.9900               | 0.0030            | 0.9430                  | 0.3000              |
| **ResNet101V2**      | 0.9303               | 0.2472            | 0.9022                  | 0.2870              |
| **InceptionResNetV2**| 0.9483               | 0.1084            | 0.9339                  | 0.2285              |
| **VGG-16**           | 0.9754               | 0.1174            | 0.9848                  | 0.0739              |

---

### **Evaluation Metrics for Deep Learning Models**

| **Model**           | **Accuracy** | **Precision** | **Recall** | **F1-Score** |
|----------------------|-------------|---------------|------------|--------------|
| **Custom CNN**       | 0.7903      | 0.75          | 0.81       | 0.7788       |
| **DenseNet201**      | 0.9414      | 0.9416        | 0.9411     | 0.9413       |
| **ResNet101V2**      | 0.9203      | 0.89          | 0.91       | 0.8998       |
| **InceptionResNetV2**| 0.9583      | 0.94          | 0.96       | 0.9498       |
| **VGG-16**           | 0.9848      | 0.98          | 0.97       | 0.9749       |

---

### **Machine Learning Models Performance**

| **Model**             | **Accuracy** |
|------------------------|-------------|
| **Logistic Regression**| 0.9830      |
| **Random Forest**      | 0.9830      |
| **Decision Tree**      | 0.997       |

## Segmentation Performance Metrics for Various Classes

| **Class** | **Precision** | **Recall** | **F1-Score** | **mAP50** | **mAP50-95** |
|-----------|---------------|------------|--------------|-----------|--------------|
| **All**   | 0.500         | 0.648      | 0.56         | 0.538     | 0.303        |
| **AKIEC** | 0.334         | 0.423      | 0.37         | 0.261     | 0.168        |
| **BCC**   | 0.425         | 0.829      | 0.56         | 0.468     | 0.229        |
| **BKL**   | 0.428         | 0.533      | 0.47         | 0.433     | 0.183        |
| **DF**    | 0.506         | 0.625      | 0.55         | 0.600     | 0.312        |
| **MEL**   | 0.451         | 0.480      | 0.46         | 0.424     | 0.275        |
| **NV**    | 0.435         | 0.815      | 0.56         | 0.677     | 0.417        |
| **VASC**  | 0.923         | 0.828      | 0.87         | 0.906     | 0.543        |


# Key Takeaways

Deep Learning Models:

* VGG-16 achieved the highest validation accuracy (98.48%) and F1-score (0.9749), making it the top-performing model.
* InceptionResNetV2 demonstrated balanced performance with 95.83% accuracy and an F1-score of 0.9498.

Machine Learning Models:

* Decision Tree achieved the best accuracy (99.7%) among classical machine learning approaches.
* Logistic Regression and Random Forest also showed strong performance (98.3% accuracy each).
* These results underscore the effectiveness of both deep learning and machine learning models in addressing skin disease classification tasks.
