# Automated-Essay-Scoring-2.0-with-Keras_NLP-and-LSTM
Enhancing automated essay scoring with advanced AI techniques using Keras-NLP and LSTM, aimed at improving educational outcomes through accurate assessment of student essays.

<div align="center"><img src="https://keras.io/img/logo-small.png" alt="Keras logo" width="100"><br/>
This starter notebook is provided by the Keras team.</div>

# Automated Essay Scoring with KerasNLP and Keras

<div align="center">
    <img src="https://i.ibb.co/BrZf1MC/AESv2.jpg" alt="Automated Essay Scoring">
</div>

In this project, we aim to develop an AI model that can score student essays, enhancing student learning outcomes. This project builds on previous competitions to improve essay scoring algorithms. We will guide you through the process of fine-tuning the **DebertaV3** model using **Ordinal Regression/Classification** to score student essays with KerasNLP.

## Project Overview

This repository contains:

- A comprehensive guide to fine-tuning the DebertaV3 model
- Training and inference notebooks
- Visualizations of model performance and architecture

**Note**: This notebook is backend-agnostic, supporting TensorFlow, PyTorch, and JAX backends. Best performance is achieved with `JAX`. For more details, explore the [Keras](https://keras.io/keras_3/) and [KerasNLP](https://keras.io/keras_nlp/) documentation.

### Model Training and Inference

Find the training and inference notebook in the [/notebooks](./notebooks) directory. You can also access it on Kaggle [here](https://www.kaggle.com/code/awsaf49/aes-2-0-kerasnlp-starter).

### Results and Visualizations

#### Model Loss (Train & Validation)

![Model Loss](results/loss_plot.png)

#### Workflow Diagram

![Workflow](results/workflow_diagram.png)

#### Model Architecture

![Model Architecture](results/model_architecture.png)

### Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

