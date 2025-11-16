Hybrid CNN-Based Dinosaur Image Classification

This project demonstrates that a Hybrid Convolutional Neural Network (Hybrid-CNN) architecture performs better than any individual CNN model for dinosaur image classification.

The dataset contained ~2,400 dinosaur images, covering multiple species.
The goal was to compare:

Individual CNN models

A Hybrid CNN architecture (combining best-performing layers)

The Hybrid model achieved higher accuracy, improved ROC performance, and better generalization.

📚 Dataset

Approximately 2,400 dinosaur images

Multiple dinosaur classes

Images resized and augmented for training

Balanced dataset after preprocessing

(Dataset cannot be uploaded here due to size)

🧠 Models Used
1. Individual CNN Models

Examples (depending on your notebook):

VGG-style CNN

Simple 3-layer CNN

LeNet-inspired architecture

ResNet-like block (if used)

Each model was trained separately and evaluated.

2. Hybrid CNN Model (Main Contribution)

The Hybrid CNN was formed by merging the strongest feature extraction layers from the individual models.

Key improvements:

Deeper, richer feature maps

Reduced overfitting

Better ROC-AUC score

Higher accuracy on validation/test sets

📊 Evaluation Metrics

The project used:

ROC Curves for all models

AUC Score

Accuracy

Precision / Recall / F1-score

Confusion Matrix

The Hybrid CNN consistently outperformed individual CNNs.

📈 Results

Hybrid CNN Accuracy: Higher than all individual models

AUC Score: Best performing

ROC Curve: Steeper and more dominant

Improved generalization on unseen images
