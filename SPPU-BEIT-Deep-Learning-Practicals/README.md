# SPPU Deep Learning Practicals

This repository contains six Deep Learning practicals implemented using Python and Jupyter Notebook.

## Practicals

1. Study of Deep Learning Packages (TensorFlow, Keras, Theano and PyTorch)
2. Feedforward Neural Network using Keras/TensorFlow and MNIST
3. Image Classification using CNN and MNIST
4. Autoencoder for Anomaly Detection using MNIST
5. Continuous Bag of Words (CBOW) using Word2Vec
6. Object Detection using Transfer Learning with YOLOv8

## Requirements

Install the packages needed for the practical you want to run:

```bash
pip install tensorflow keras numpy matplotlib scikit-learn
pip install gensim nltk
pip install ultralytics torch
```

Open the `.ipynb` files in Jupyter Notebook or JupyterLab and run the cells from top to bottom.

## Notes

- MNIST and the NLTK Gutenberg corpus are downloaded automatically when the notebook runs.
- Practical 6 uses the pretrained YOLOv8n model and the COCO128 dataset. The first run may download model weights and dataset files.
- Practical 6 uses YOLOv8's built-in detection head; it does not manually add a separate custom classifier.
