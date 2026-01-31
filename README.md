Microplastic Image Segmentation

This repository contains the implementation and experimental framework for microscopic microplastic image segmentation using a stage-adaptive attention encoder–decoder network with EfficientNetV2 as the backbone and multi-resolution feature fusion. The work focuses on addressing extreme foreground–background imbalance, translucent particles, and complex particle morphology in microscopic imagery.

Key Contributions

EfficientNetV2-B3based encoder with training-aware scaling

Stage-adaptive channel and spatial attention mechanisms

Multi-resolution feature fusion for thin and elongated particle structures

Boundary-aware segmentation to improve edge delineation

Robust performance under severe class imbalance

Network Architecture

The proposed model follows an encoder–decoder design:

Encoder: EfficientNetV2 (B0–B3 variants supported)

Attention: Channel-wise and spatial attention at multiple stages

Decoder: Progressive upsampling with multi-scale feature fusion

Model Link: https://drive.google.com/drive/folders/1cCCAMm7Bi4_wamoeyrW7slhyIU5sVXYJ
