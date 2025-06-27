My first ever deep learning project completed and with the acuuracy of 97% and above, the above model helps in detecting curvical cancer

 **Base Model**: MobileNetV2 (Pretrained on ImageNet)
- **Why MobileNetV2?**
  - Lightweight and optimized for mobile/edge devices
  - Fast training and inference
  - Ideal for deployment on low-resource devices
- **Input Size**: 224x224
- **Classification Head**:
  - GlobalAveragePooling2D
  - Dense → LeakyReLU → Dropout
  - Final Softmax activation
