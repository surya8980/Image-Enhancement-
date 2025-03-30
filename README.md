# Image Enhancement Models

## Overview
This repository contains implementations of image enhancement models, including:
- **SRCNN (Super-Resolution Convolutional Neural Network)**
- **SRGAN (Super-Resolution Generative Adversarial Network)**
- **Multi-Headed Attention Model for Image Enhancement**

Each model aims to improve the resolution and quality of low-resolution images using deep learning techniques.

## Models
### 1. SRCNN
- A deep learning model for single-image super-resolution.
- Uses a three-layer CNN to enhance low-resolution images.
- Trained on high-quality datasets to reconstruct fine details.

### 2. SRGAN
- A GAN-based approach for super-resolution.
- Consists of a generator (for image enhancement) and a discriminator (for adversarial training).
- Produces high-resolution, photo-realistic images.

### 3. Multi-Headed Attention Model
- Utilizes attention mechanisms to enhance image details.
- Designed to improve fine-grained textures and structures.
- Uses self-attention layers to focus on important features in the image.

## Dataset
- **Training Dataset:** DIV2K, Image super resolution datasets.
- **Preprocessing:**
  - Downscaling high-resolution images using bicubic interpolation.
  - Normalization and augmentation applied for better generalization.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/surya8980/Image-Enhancement-Using-Deep-Learning.git
   cd Image-Enhancement-Using-Deep-Learning
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the training script for the desired model:
   ```sh
   python train_srcnn.py  # For SRCNN
   python train_srgan.py  # For SRGAN
   python train_attention.py  # For Multi-Headed Attention Model
   ```

## Usage
- **Deploying as a Flask/Streamlit App:**
  ```sh
  python app.py
  ```
## Demo
![WhatsApp Image 2025-03-30 at 09 32 40_31a43daa](https://github.com/user-attachments/assets/c4d539aa-d9d8-485a-a558-d8cf2c20008f)
![WhatsApp Image 2025-03-30 at 09 32 40_f9228c04](https://github.com/user-attachments/assets/a01c4579-530e-45c1-8640-eb7cf70e6959)

## Evaluation Metrics
- Peak Signal-to-Noise Ratio (PSNR)
- Structural Similarity Index (SSIM)

## Results & Visualizations
- Model training loss and accuracy graphs.
- Comparison between low-resolution input and high-resolution output.
- Performance analysis using PSNR, SSIM.

## Future Work
- Improve model generalization with additional datasets.
- Optimize inference time for real-time applications.
- Deploy models on cloud-based platforms.

## Contributors
- **D Surya Prakash Reddy** ([@surya8980](https://github.com/surya8980))

## License
This project is licensed under the MIT License - see the LICENSE file for details.

