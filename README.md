# Transformer Network Application: Named-Entity Recognition (NER)

This repository contains my solution to the **Named-Entity Recognition** lab from Week 4 of the DeepLearning.AI [Sequence Models](https://www.coursera.org/learn/nlp-sequence-models) course.

The goal of this lab is to build a Transformer-based model that identifies named entities (such as persons, locations, and organizations) in text using TensorFlow/Keras.

---

##  Contents

- `NER_notebook.ipynb` – The main notebook including preprocessing, model building, training, and evaluation.
- `config.json` – Model architecture configuration file.
- `data/` – Folder containing the NER dataset used in this lab.

---

##  What I Did

In this lab, I:
- Preprocessed the dataset using tokenization and padding.
- Built a custom Transformer-based model for NER.
- Trained and evaluated the model's ability to recognize entities from sentences.

---

##  Note on Removed Model Files

To keep this repository lightweight and under GitHub’s file size limit, I have removed the following large model files:

- `tf_model.h5` – Trained model weights
- `_tf_model.h5` – Alternative copy of the model
- `W4A2-UGL-NER.tar.gz` – A compressed archive of the trained model

---

##  How to Recreate the Model

To run the notebook end-to-end and create your own model file:

1. Launch the notebook and execute all cells.
2. This will train the model and automatically save `tf_model.h5` inside the following directory:

