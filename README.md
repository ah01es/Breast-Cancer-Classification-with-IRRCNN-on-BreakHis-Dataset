# Breast Cancer Classification from Histopathological Images using IRRCNN

This project presents a complete implementation of the **Inception Recurrent Residual Convolutional Neural Network (IRRCNN)** architecture for classifying breast cancer from histopathological images.

## Background

The architecture and methodology are based on the paper:

**Breast Cancer Classification from Histopathological Images with Inception Recurrent Residual Convolutional Neural Network**  
Md Zahangir Alom et al.

Unfortunately, the official code repository for this paper is not publicly available. Therefore, I have independently implemented the entire model and training pipeline from scratch. The model is trained and evaluated on the BreakHis dataset.

## Dataset

The model is trained and evaluated on the **BreakHis** dataset, a well-known benchmark for histopathological breast cancer classification.

You can download the BreakHis dataset from Kaggle at:  
[https://www.kaggle.com/datasets/ambarish/breakhis](https://www.kaggle.com/datasets/ambarish/breakhis)

## Implementation Details

- The IRRCNN model combines Inception modules, recurrent layers, and residual connections to effectively learn spatial and contextual features from pathology images.
- Training scripts include data preprocessing, augmentation, model training, and evaluation.
- Hyperparameters and experimental settings follow those reported in the original paper.

## Usage

Instructions to run training and evaluation will be provided here.

## Notes

- This implementation is an independent reproduction of the IRRCNN architecture without access to the original codebase.
- Results and performance metrics are comparable to those reported in the paper.

---

If you have any questions or want to contribute, feel free to open an issue or pull request.

