# Pneumonia Detection with CheXNet and Grad-CAM 

This project uses **CheXNet (DenseNet121)** to classify chest X-ray images as **Normal** or **Pneumonia**, and applies **Grad-CAM** to highlight the lung regions influencing the model's predictions.

## Features
- Fine-tuned DenseNet121 pre-trained on ImageNet
- Trained on chest X-ray datasets (e.g., Kaggle)
- Grad-CAM heatmaps for interpretability
- Visualizations for training performance and evaluation

---

## Installation

```bash
git clone https://github.com/privmh/pneumonia-detection-chexnet.git
cd pneumonia-detection-chexnet

# Create and activate a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or use venv\Scripts\activate on Windows

pip install -r requirements.txt

## Usage
1. Train the Model

python CAM_ChexNet.py

2. Run Inference

python chexnet_inference.py --image_path sample_images/Normal.jpeg

3. Generate Grad-CAM

python grad_cam.py --image_path sample_images/Pneumonia.jpeg

## Evaluation Metrics

    Accuracy

    Confusion Matrix

    ROC-AUC

    Classification Report

## References

    CheXNet Paper (Rajpurkar et al.)

    Grad-CAM (Selvaraju et al.)

## License
MIT
