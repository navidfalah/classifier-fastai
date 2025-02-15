# Image Classification with FastAI 🖼️🤖

This project demonstrates **image classification** using the **FastAI** library on the **Oxford-IIIT Pet Dataset**. The goal is to classify images of pets into different categories using a pre-trained **ResNet34** model. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **FastAI** to build and train an image classification model. 🤖📸
- Leverages the **Oxford-IIIT Pet Dataset** for training and validation. 🧠🔍
- Implements data augmentation, model training, and evaluation. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install fastai
```

---

## Usage 🖥️

1. **Load Dataset**: The script downloads and loads the Oxford-IIIT Pet Dataset.
2. **Preprocess Data**: Applies data augmentation and splits the data into training and validation sets.
3. **Build Model**: Defines and trains a ResNet34 model using transfer learning.
4. **Evaluate Model**: Evaluates the model's performance using accuracy and confusion matrices.
5. **Interactive Interface**: Provides an interface to upload and classify pet images.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Downloads and preprocesses the Oxford-IIIT Pet Dataset.
  - Applies data augmentation and normalization.

- **Model Definition**:
  - Uses a pre-trained ResNet34 model for transfer learning.
  - Adds a custom classification head for pet classification.

- **Training**:
  - Trains the model using the training set.
  - Tracks training and validation accuracy.

- **Evaluation**:
  - Evaluates the model's performance on the validation set.
  - Visualizes results using confusion matrices and top losses.

- **Interactive Interface**:
  - Provides an interface to upload and classify pet images.

---

## Results 📊

- **Training/Validation Accuracy**: The model achieves high accuracy on the training and validation sets.
- **Confusion Matrix**: Visualizes the model's predictions against actual labels.
- **Interactive Classification**: Allows users to upload images and get predictions.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 1/3: train_loss=0.123, valid_loss=0.045, error_rate=0.02
Epoch 2/3: train_loss=0.045, valid_loss=0.032, error_rate=0.01
```

---

## Dependencies 📦

- `fastai`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
