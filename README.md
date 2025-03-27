# Breast Cancer Classifier

Built a neural network to classify breast cancer tumors—benign or malignant—using the Wisconsin Breast Cancer Dataset. “AI’s here to crunch data and save lives,” I’d say. This bad boy runs in your browser, hitting 90%+ accuracy after 100 epochs. Powered by TensorFlow.js, JavaScript, and a Python HTTP server, it’s a lean, mean prediction machine!

## Overview

- **Dataset**: Wisconsin Breast Cancer Dataset (455 training samples, 114 testing samples, 30 features like radius, texture, etc.).
- **Model**: 3-layer neural net (30 → 16 → 8 → 1) with ReLU and sigmoid activations.
- **Tech Stack**: TensorFlow.js, JavaScript, Python (HTTP server).
- **Performance**: 90%+ accuracy, trained for 100 epochs with `binaryCrossentropy` loss and `rmsprop` optimizer.

## Files

- **`C1_W1_Assignment.html`**: The core script—loads data, builds the model, trains it, and saves the output.
- **`data/wdbc-train.csv`**: Training data (455 samples).
- **`data/wdbc-test.csv`**: Testing data (114 samples).
- **`my_model.json`**: Trained model architecture (generated post-training).
- **`my_model.weights.bin`**: Trained weights (generated post-training).

## How to Run

1. **Clone the Repo**  
   ```bash
   git clone https://github.com/ahmershah29/breast-cancer-classifier.git
   cd breast-cancer-classifier
