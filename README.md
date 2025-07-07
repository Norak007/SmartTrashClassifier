# SmartTrashClassifier
A smart image classification project that detects whether waste is plastic, paper, or metal using a Keras model trained with Teachable Machine.


The model detects whether an object in an image is:
- ورق
- معدن
- بلاستيك

## How it Works

The model was trained using sample images of different types of materials.  
When you run the script, it loads the trained model and predicts the class of the given image.

## Files

- `keras_model.h5` – the trained model file.
- `labels.txt` – the labels of the classes.
- `classify_image.py` – the Python script that loads the model and classifies an image.
- `اختبار بلاستيك.jpg` – sample images used for testing.
