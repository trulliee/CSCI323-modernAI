# CSCI323-modernAI
Scene Recognition
# Scene Recognition with Transfer Learning

This project applies transfer learning techniques to classify indoor scenes using the Kaggle Indoor CVPR09 dataset. Four pretrained models were evaluated for comparative performance: **Vision Transformer**, **ConvNeXt**, **EfficientNetB0**, and **Swin-Small**.

## 🧠 Project Highlights
- Dataset: [Kaggle Indoor CVPR09](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)
- Models: ViT, ConvNeXt, EfficientNetB0, Swin-Small
- Framework: TensorFlow & Keras
- Platform: Jupyter Notebook

## 🔧 Methods Used
- Image preprocessing & augmentation
- Transfer learning with pretrained weights
- Model training with frozen & fine-tuned layers
- Validation accuracy tracking across models

## 📁 Files Included
- `scene_recognition.ipynb`: Main notebook with model training + evaluation
- `results/`: (optional) Screenshots of confusion matrix, accuracy graphs

## 📝 Notes
Due to resource limitations, training epochs were kept low. Pretrained models were used to balance accuracy with feasibility.

