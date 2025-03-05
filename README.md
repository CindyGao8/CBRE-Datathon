# CBRE-Datathon-2024


## Motivation
Within rapid development of E-Commerce during pandemic, timely construction of industrial warehouses is essential. A precise model for estimating construction time ensures efficient planning and resource allocation, vital for meeting the demands of rapidly growing online retail. With accurate projections, businesses can strategize their supply chain management effectively, optimizing delivery schedules and customer satisfaction. 
This project aims to classify warehouse completion levels using a ResNet deep learning model. The dataset consists of warehouse images filtered based on IP addresses, labeled with completion levels ranging from 1 (least complete) to 5 (fully complete). The model is trained to predict the completion status of warehouses using image data.

## Approach

### Data Collection:
Extract warehouse images based on IP addresses.
Organize images into categories based on completion levels (1-5).
Data Preprocessing:

### Resize images.
Normalize pixel values.
Augment data to improve model performance

### Model Training (ResNet)
Use a pretrained ResNet model (ResNet18/ResNet50).
Fine-tune on labeled warehouse images.
Optimize training using loss functions and learning rate scheduling.

### Evaluation & Testing:
Assess model performance using accuracy, precision, and recall.
Test on unseen warehouse images and get ROC. 

## Results
<img width="374" alt="Screenshot 2025-03-05 at 4 36 40 PM" src="https://github.com/user-attachments/assets/f552ed86-045b-45fb-b17b-fe50b1b8c7e6" />

Final Training Accuracy: ~0.7 to 0.75
Final Validation Accuracy: ~0.75 to 0.8
Key Observations:
The model shows steady improvement over 100 epochs.
Validation accuracy fluctuates, suggesting potential overfitting



