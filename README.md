# GRU-Based Text Generation

This repository implements a GRU-based Recurrent Neural Network (RNN) for text generation. The model generates Shakespeare-like text by learning from a dataset of Shakespeare's works.

## Features

- **Text Preprocessing**: Cleans text, builds vocabulary, and converts text into sequences.
- **Sequence Batching**: Creates input-output pairs with configurable sequence lengths.
- **Custom GRU Model**: Implements a GRU-based model with embedding, GRU, and dense layers.
- **Training and Saving**: Trains the model and saves weights for future use.
- **Text Generation**: Generates text sequences based on learned patterns.

## Files

1. **`GRU_TextGeneration.ipynb`**: Python script implementing the GRU-based text generation pipeline.
2. **Dataset**: `shakespeare_data.txt` - Text corpus of Shakespeare's works.

## Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:AbdulrahmanAhmed20072/TextGeneration-GRU-Model.git
   ```
2. Install the required Python packages:
   ```bash
   pip install numpy tensorflow
   ```

## Usage

1. Preprocess the text to create sequences and vocabulary.
2. Train the GRU-based model on the preprocessed data.
3. Use the trained model to generate text sequences.

Run the script:
```bash
python GRU_TextGeneration.ipynb
```

## Outputs

- GRU-based model trained to generate Shakespeare-like text.
- Generated text samples based on input sequences.
- Model weights saved as `model.weights.h5`.

## Example

Input Sequence:
```
To be, or not
```

Generated Text:
```
To be, or not to be, that is the question.
```
