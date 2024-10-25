# Ensemb-Care: AI Diagnosis for Respiratory Conditions
This project focuses on developing a deep learning-based image classification system designed to identify three classes from medical images: PNEUMONIA, NORMAL, and COVID. Leveraging ensemble learning, the system analyzes chest X-ray images using three powerful pretrained models: MobileNet, ResNet, and VGG16. This approach harnesses convolutional layers for feature extraction and dense layers for classification, enhancing prediction accuracy and providing a reliable, automated diagnostic tool.

**Advantages**

High Accuracy: Combining MobileNet, ResNet, and VGG16 in an ensemble configuration improves diagnostic accuracy by utilizing each model’s unique strengths.
Automation: The system automates image classification, making it quicker for medical professionals to interpret X-ray results and identify respiratory conditions.
User-Friendly Interface: With a simple upload feature, users can easily obtain a diagnosis, making the system accessible even to those without a technical background.
Cost-Effective: Reduces the need for costly, time-consuming laboratory tests, enabling more affordable diagnostic solutions.
Scalable: The use of pretrained models makes it possible to adapt and improve the system as new respiratory conditions and datasets emerge.

**Disadvantages**

Limited Dataset Variability: If the training dataset does not represent diverse demographics, there may be limitations in accurately diagnosing patients from underrepresented groups.
Dependence on X-ray Quality: The model’s accuracy may be compromised if the X-ray images are low quality, leading to potential diagnostic inaccuracies.
Hardware and Computation Requirements: Running an ensemble of deep learning models may require substantial computational resources, which can be a challenge in resource-limited settings.
Black-Box Model: Deep learning models lack transparency, which can make it challenging for healthcare providers to trust the decision-making process without clear interpretability.

**Results**

Model Accuracy: The ensemble model, incorporating MobileNet, ResNet, and VGG16, achieved a high classification accuracy, outperforming each individual model in detecting COVID, Pneumonia, and normal conditions.
Improved Prediction Consistency: By using ensemble learning, ENSEMB-CARE shows improved consistency across different types of respiratory conditions, indicating the robustness of the model in various scenarios.
User Testing: Initial tests show that the interface is intuitive, with users able to upload X-ray images and receive reliable predictions quickly.

ENSEMB-CARE exemplifies the potential of AI to assist healthcare professionals in making timely, data-driven decisions that improve patient outcomes and support early intervention in respiratory conditions.
