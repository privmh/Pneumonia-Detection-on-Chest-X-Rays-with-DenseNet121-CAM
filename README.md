# Pneumonia Detection with CheXNet and Grad-CAM 

This project uses **CheXNet (DenseNet121)** to classify chest X-ray images as **Normal** or **Pneumonia**, and applies **Grad-CAM** to highlight the lung regions influencing the model's predictions.

## Features
- Fine-tuned DenseNet121 pre-trained on ImageNet
- Trained on chest X-ray datasets (e.g., Kaggle)
- Grad-CAM heatmaps for interpretability
- Visualizations for training performance and evaluation

## Evaluation Metrics
- Accuracy
- Confusion Matrix
- ROC-AUC
- Classification Report
  
## Dataset

This project uses the **Chest X-Ray Images (Pneumonia)** dataset.
You can download it from the Kaggle notebook below, which includes the full preprocessing pipeline:[CheXNet Radiologist-Level Pneumonia Detection (Kaggle)](https://www.kaggle.com/code/ashishpatel26/chexnet-radiologist-level-pneumonia-detection)


## References
- CheXNet Paper: https://arxiv.org/abs/1711.05225
- Grad-CAM: https://arxiv.org/abs/1610.02391
## License
- MIT
