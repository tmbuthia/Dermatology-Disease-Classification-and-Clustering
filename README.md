# Dermatology-Disease-Classification-and-Clustering
This project involves classifying and clustering dermatological diseases based on clinical and histopathological features. 
# Project Overview
The dataset contains attributes related to both clinical observations and histopathological findings for various erythemato-squamous diseases, such as psoriasis, seborrheic dermatitis, lichen planus, 
pityriasis rosea, chronic dermatitis, and pityriasis rubra pilaris. The goal is to explore the relationships between these features and the disease type using several machine learning techniques.
# Dataset
The dataset includes 34 attributes and a class label for the disease type. Attributes are categorized as follows:
![image](https://github.com/user-attachments/assets/c91132fc-5c1f-4471-a743-239a771bebd5)
# Objectives
Gradient Descent Regression: Use gradient descent to model the relationship between the patient's age and the disease type.
Random Forest Classification: Apply Random Forest to classify disease types based on clinical and histopathological attributes.
k-Nearest Neighbors (kNN) Classification: Use kNN for classification with both clinical and histopathological attributes.
Clustering: Apply two clustering algorithms (K-Means and Agglomerative Clustering) to explore the underlying structure of the dataset.
# Implementation
1. Gradient Descent Regression (Model 1)
![image](https://github.com/user-attachments/assets/f8b67bfa-20e1-4f7a-9baa-a06385f08bd5)

2. Random Forest Classification (Model 2)
 ![image](https://github.com/user-attachments/assets/f6a95a50-b156-4ba2-b958-9147ef031c02)

3. k-Nearest Neighbors (kNN) Classification (Model 3)
 ![image](https://github.com/user-attachments/assets/5960823a-ee59-41a0-a9a9-4915702567d7) 
4. Clustering (Model 4 & Model 5)
  ![image](https://github.com/user-attachments/assets/a12d9e74-beae-4c38-b36e-822ce29a329c)
# Results
a.Model 1 (Gradient Descent Regression): Learned a linear relationship between age and disease type. The final model parameters include weights and bias, with a basic understanding of the influence of age on disease type.

b.Model 2 (Random Forest Classification): Achieved an accuracy of 98.65%, indicating high performance in classifying disease types based on all features.

c.Model 3 (kNN Classification): Achieved an accuracy of 82.43%, which is slightly lower than Random Forest but still effective in classification.

d.Model 4 & Model 5 (Clustering): K-Means and Agglomerative Clustering both had moderate silhouette scores and low ARI scores, suggesting that clustering did not capture distinct disease types effectively.
# Visualization
![image](https://github.com/user-attachments/assets/6cddcf9b-385b-4a1f-88e6-1c7df2c5ebce)
# Conclusion
The combination of regression, classification, and clustering approaches provides a comprehensive view of the dataset. Gradient Descent and classification models show good performance in predicting disease types, while clustering models reveal
challenges in identifying inherent groupings within the data. This multi-faceted approach helps in understanding the relationships and structures in dermatological disease data.
# Acknowledgments
The dataset was provided for the study of erythemato-squamous diseases, and the methods used include standard machine learning techniques for classification and clustering.
