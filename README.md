# MLP Test Speech

This project is focused on speech recognition using machine learning techniques. The main goal is to classify different speech commands using a neural network model.

## Project Structure

```
P2.ipynb
requirements.txt
dataset/
TESTARE_VOICE/
```

## Notebooks

- `P2.ipynb`: Main notebook for data preparation, model training, and evaluation. The evaluation can also be performed using a microphone as demonstrated in the notebook.

## Directories

- `dataset/`: Contains the speech command dataset.
- `TESTARE_VOICE/`: Directory for storing test voice recordings.

## Requirements

Install the required packages using:

```sh
pip install -r requirements.txt
```

## Usage

1. **Prepare the Dataset**: Ensure the dataset is placed in the `dataset/` directory.
2. **Train the Model**: Use the `P2.ipynb` notebook to train the model.
3. **Evaluate the Model**: Evaluate the model using the test voice recordings in the `TESTARE_VOICE/` directory. The notebook also includes an example of how to evaluate the model using a microphone.

## Example

To train the model, open `P2.ipynb` and run all the cells. The notebook includes data loading, preprocessing, model training, and evaluation steps. For evaluation using a microphone, follow the instructions provided in the notebook.
