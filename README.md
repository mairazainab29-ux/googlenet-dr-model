# GoogLeNet (Inception v1) for Diabetic Retinopathy Detection

Binary classification of fundus images: DR vs No_DR.

- Model: googlenet_best.keras
- Notebook: notebook98c64cd2d1.ipynb
- Framework: TensorFlow / Keras
- Trained on Kaggle (GNDataset)

## Load the model

from tensorflow.keras.models import load_model
model = load_model("googlenet_best.keras")
