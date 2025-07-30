# 🌿 Deep Learning-Based Detection of *Hevea brasiliensis* Leaf Diseases for Sustainable Cultivation

This project focuses on the early detection and classification of rubber plant (*Hevea brasiliensis*) leaf diseases using deep learning techniques. By automating disease identification through image analysis, this tool supports sustainable rubber cultivation by enabling early intervention and reducing crop loss.

## Project Structure

├── Data augmentation/ # Data preprocessing and augmentation scripts
├── EfficientNet/ # Implementation using EfficientNet architecture
├── Resnet50/ # Implementation using ResNet50 architecture
├── VGG16/ # Implementation using VGG16 architecture
├── Yolo/ # YOLO-based object detection model
└── .ipynb_checkpoints/ # Jupyter notebook checkpoints

## Models Used

- **VGG16** – CNN-based feature extractor and classifier
- **ResNet50** – Residual learning for deeper networks
- **EfficientNet** – Optimized scaling for accuracy and efficiency
- **YOLO** – Real-time object detection for localized leaf disease detection

## Data Augmentation

Data augmentation techniques such as rotation, flipping, zooming, and contrast adjustment were applied to increase dataset variability and improve model generalization.

## Goal

- Detect four common rubber leaf diseases in various environmental conditions
- Evaluate model performance using accuracy, precision, recall, and F1-score
- Enable practical deployment in rubber nurseries and plantations

## Evaluation Metrics

- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

## 🛠Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib, NumPy
- Jupyter Notebook
