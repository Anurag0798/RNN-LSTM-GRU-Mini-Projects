# RNN / LSTM / GRU Mini Projects

A collection of small, practical projects that demonstrate the use of Recurrent Neural Networks (RNN), Long Short-Term Memory units (LSTM), and Gated Recurrent Units (GRU) for common Natural Language Processing (NLP) tasks using TensorFlow and Keras. These notebook-based projects are ideal for learning, experimentation, and hands-on demonstrations of deep learning for sequence data.

## Projects Included

- **Next Word Predictor**
  - Builds a next-word prediction model using Embedding + LSTM layers.
  - Easily swap LSTM for GRU or SimpleRNN to compare architectures.
  - Includes step-by-step data preprocessing, model creation, training, and testing.

- **Sentiment Analyzer**
  - Implements sentiment classification (positive/negative) with Embedding + RNN/LSTM/GRU.
  - Full training and evaluation workflow with metrics and logs.
  - Adjustable architecture for RNN cell type and sequence length.

## Features

- **End-to-End NLP Examples:**  
  From tokenization and data preparation to neural network training and evaluation.

- **RNN Benchmarks:**  
  Quickly switch between LSTM, GRU, and SimpleRNN layers to benchmark performance.

- **Beginner Friendly:**  
  Notebooks are commented and explained, with code cells and outputs for easy stepwise execution.

- **Extensible:**  
  Designed to be a base for experimentation - use your own data, tweak model parameters, or extend to more complex problems.

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Anurag0798/RNN-LSTM-GRU-Mini-Projects.git

   cd RNN-LSTM-GRU-Mini-Projects
   ```

2. **(Optional) Create and activate a virtual environment**
   ```bash
   python -m venv .venv

   # On macOS/Linux
   source .venv/bin/activate

   # On Windows
   .venv\Scripts\Activate.ps1
   ```

3. **Install requirements**
   ```bash
   pip install tensorflow numpy matplotlib scikit-learn
   ```

4. **Run the notebooks**
   Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Open `Next_Word_Predictor.ipynb` or `Sentiment_Analyser.ipynb` and run cells step-by-step.

## Requirements

- Python 3.7+
- tensorflow
- numpy
- matplotlib
- scikit-learn

All packages can be installed via `requirements.txt`.

## Project Structure

```
.
├── Next_Word_Predictor.ipynb      # Next-word prediction notebook
├── Sentiment_Analyser.ipynb       # Sentiment classification notebook
└── README.md                      # This file
```
## Usage & Customization

- Tweak the corpus, sequence length, model type (LSTM/GRU/RNN), or training parameters as you wish in the notebooks.
- For quick architecture changes, simply swap `LSTM()` with `GRU()` or `SimpleRNN()` in the model definition.
- Use your own text data for more personalized or powerful models.
- Visualize loss and accuracy to analyze performance.

## Contributing

Contributions are welcome!  
- Fork the repo, create a branch, and open a pull request for new notebooks, improvements, or bug fixes.
- Please comment your code and keep examples minimal and instructive.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

- Developed using TensorFlow and Keras.
- Example workflows inspired by classic NLP tutorials and Keras guides.
