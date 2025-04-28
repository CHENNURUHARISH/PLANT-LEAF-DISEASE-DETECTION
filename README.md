# PLANT-LEAF-DISEASE-DETECTION

Plant diseases pose a major challenge for farmers worldwide, leading to significant crop losses and threatening food security. Early and accurate detection is crucial for effective disease management however, traditional methods rely heavily on expert inspection, which is time-consuming and impractical for large-scale monitoring. The aim of this project is to automate plant disease detection using deep learning techniques, specifically Convolutional Neural Networks (CNNs). The dataset used consists of images of healthy and diseased plant leaves across various species, sourced from publicly available plant disease image repositories. The input format to the model is pre-processed RGB images resized to a standard dimension (e.g., 224x224 pixels), and the output format is a classification label indicating the type of disease or healthy status of the plant. In this study, I compare two popular CNN architectures, MobileNetV2 and VGG16, to determine which model offers the best trade-off between accuracy, speed, and computational efficiency.
Data Format: Images (RGB format)

Dataset: 

training dataset: https://drive.google.com/drive/folders/13IYFvrag6Snq8qVjZwDvxmNu1UiesnZI?usp=drive_link


validation dataset: https://drive.google.com/drive/folders/1kZk8WMUZtc0rTvdvrFMbgnAhcIth2a_e?usp=drive_link

Preprocessing
Normalization of pixel values (0-255 scaled to 0-1)


Data augmentation (optional) to improve model generalization

output:
VGG16: ![image](https://github.com/user-attachments/assets/81a87ab0-0c1c-4545-9298-ae0589ee96e1)
MOBILENET:![image](https://github.com/user-attachments/assets/f99a56b8-d950-4748-85c0-35b8d41a0a33)
:![image](https://github.com/user-attachments/assets/cc77f276-64d3-43be-a28e-ae2fa2fa7cbd)
   ![image](https://github.com/user-attachments/assets/aa122701-48a7-4506-93db-070831e7cf4d)

Visualization for CNN:

confusion matrix: ![image](https://github.com/user-attachments/assets/592d5a02-cd39-436f-b940-1e1f06ff299e)
 ![image](https://github.com/user-attachments/assets/e4289035-6392-4639-bc95-9d4f6c18c299)


 ![image](https://github.com/user-attachments/assets/c069fea5-0ae4-40a2-a853-473f3e7e1ca8)

conclusion:

This project shows that deep learning models like MobileNetV2 and VGG16 can effectively detect plant diseases from leaf images. MobileNetV2 is faster and better for real-time use, while VGG16 offers slightly higher accuracy. CNNs offer a powerful solution to support early disease detection and smarter farming.
