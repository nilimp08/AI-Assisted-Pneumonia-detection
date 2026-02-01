# AI-Assisted-Pneumonia-detection
AI system that looks at chest X-ray images and helps doctors detect pneumonia.
## Problem Statement
Pneumonia causes 15% of deaths in children under 5 years old globally .Rapid and accurate diagnosis is critical, but expert radiologists are  often overworked, leading to delays. Thus a Computer vision model is required that can act as a “second opinion” tool, automatically flagging Chest X-Rays that show signs of Pneumonia to prioritize them for a medical professional’s review.
## Solution
We built an AI system that acts as a second opinion. It classifies X-rays as normal, bacterial, or viral pneumonia, and highlights the infected region so doctors can verify the result. We prioritize recall to reduce false negatives, since missing a sick patient is worse than over-flagging.The 3-way classification approach provides more actionable
insights for different treatment plans.
## Tech Stack
<br>
1.Language: Python 3.10<br>
2.Deep Learning Framework: TensorFlow / Keras<br>
3.Web Interface: Streamlit<br>
4.Image Processing: OpenCV, PIL Pillow, NumPy<br>
5.Visualization: Matplotlib, Seaborn<br>
6.Algorithms & libraries<br>
7.ResNet50 Utilized Transfer Learning with a pre-trained ResNet50 architecture<br>
(trained on ImageNet) to extract high-level features from X-ray images. This
allows deep understanding even with a limited dataset.<br>
8.Data Augmentation: Implemented rotation, zoom, width/height shifts, and
horizontal flips to prevent overfitting and improve model robustness.<br>
9.-Heatmaps: grad-CAM attention heatmaps.<br>
10.Callbacks: Early Stopping, ReduceLROnPlateau, and ModelCheckpoint were used
to optimize training and ensure the best model was saved.

## Team Name
**Compile N Pray**

## Team Members
- **Shivansh Sarawgi**
- **Anusha Shree**
- **Nilimp Sharma**

