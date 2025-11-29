# Gemma 3 270M Small Language Model from Scratch

This project demonstrates how to build, train, and inference a Small Language Model (SLM) with approximately 270 million parameters from scratch, inspired by the Gemma 3 architecture.

## Overview

The notebook `Gemma_3_270_M_Small_Language_Model_Scratch_Final.ipynb` guides you through the entire process:
1.  **Importing the Dataset**: Using the TinyStories dataset.
2.  **Tokenization**: Tokenizing the dataset and creating input-output batches.
3.  **Model Architecture**: Defining the SLM architecture including Rotary Positional Embeddings (RoPE), RMSNorm, and Grouped Query Attention.
4.  **Training**: Setting up the training loop, loss function, and optimizer.
5.  **Inference**: Generating text using the trained model.

## Dataset

The project uses the [TinyStories](https://huggingface.co/datasets/roneneldan/TinyStories) dataset, which consists of short stories with a simple vocabulary, making it suitable for training smaller models.

## Installation

To run this project, you need to install the required dependencies. You can do this using pip:

```bash
pip install -r requirements.txt
```

## Usage

1.  Clone the repository or download the project files.
2.  Install the dependencies as shown above.
3.  Open the notebook `Gemma_3_270_M_Small_Language_Model_Scratch_Final.ipynb` in Jupyter Notebook or Google Colab.
4.  Run the cells sequentially to build and train the model.

## Credits

This project is presented by Vizuara.
