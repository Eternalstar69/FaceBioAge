# Face-Only Biological Age Estimation

Estimate chronological and pseudo-biological age from face images using a dual-head deep learning model (ResNet50 backbone).

---

## Description

This project predicts:

- **Chronological Age** – age from the face image.  
- **Pseudo-Biological Age** – simulated biological age based on facial features.

The model is trained on UTKFace and fine-tuned to output dual-age predictions. A Gradio interface allows easy deployment and testing.

---

## Requirements

```
pip install torch torchvision pandas pillow gradio
```
##  Usage

1.Clone the repository
```
git clone https://github.com/yourusername/FaceBioAge.git
cd FaceBioAge
```
2.Place dual_model.pth in the repo folder


3.Run the last cell in the Colab notebook to launch the Gradio interface and upload face images for prediction.

## Notes

The biological age is pseudo/simulated, not real clinical data.

Maximum age normalization used: 100 years.
