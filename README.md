# Pharmaceutical-Drug-Image-Classification-using-CNN-and-Transfer-Learning_Deep-Learning

This project aimed to classify synthetic images of pharmaceutical drugs and vitamins using deep learning. The model helps identify drugs from their images, reducing confusion and assisting the public in recognizing medications accurately. The dataset used was the Pharmaceutical Drugs and Vitamins Synthetic Images from Kaggle, consisting of labeled synthetic drug and vitamin images.

**Tools**: Python, TensorFlow, Keras, Matplotlib

**Approach**: Implemented transfer learning using EfficientNetB0 and ResNet50V2 with both fully frozen and partially frozen layers. Attention map visualization was applied to analyze which image areas influenced model predictions.

**Results**: The partially frozen ResNet50V2 achieved the best performance, with accuracy >80% and F1-scores ≥0.80 across all classes. Partial layer unfreezing significantly improved feature adaptation and focus compared to fully frozen models.

**Key Insight**: Fine-tuning pretrained models (partial freezing) greatly increases performance on domain-specific data, leading to more accurate and stable classification results.
