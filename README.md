# Google Stock Market Prediction using LSTM

This repository contains Jupyter notebooks that demonstrate how to predict Google's stock prices using Long Short-Term Memory (LSTM) networks implemented in both TensorFlow and PyTorch.

## Notebooks

- **GoogleStockLSTM-Tensorflow.ipynb**: This notebook utilizes TensorFlow to build and train an LSTM model for predicting Google's stock prices.
- **googlestocklstm-pytorch.ipynb**: This notebook employs PyTorch to construct and train an LSTM model for the same purpose.

## Getting Started

To run these notebooks on your local machine, follow the steps below:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/babakshofficial/google-stock-market-LSTM.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd google-stock-market-LSTM
   ```

3. **Install the required packages**:

   Ensure you have Python installed on your system. It's recommended to use a virtual environment to manage dependencies. You can create and activate a virtual environment using the following commands:

   ```bash
   # Create a virtual environment
   python -m venv venv

   # Activate the virtual environment
   # On Windows
   venv\Scripts\activate
   # On macOS and Linux
   source venv/bin/activate
   ```

   Once the virtual environment is activated, install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

   *Note: The `requirements.txt` file should list all the necessary packages. If it's not present in the repository, you can install the packages manually as needed.*

4. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

   This command will open the Jupyter Notebook interface in your default web browser.

5. **Open and run the notebooks**:

   In the Jupyter interface, open either `GoogleStockLSTM-Tensorflow.ipynb` or `googlestocklstm-pytorch.ipynb` and execute the cells to train the LSTM model and make predictions.

## Data

The notebooks are designed to fetch Google's stock price data using the Yahoo Finance API. Ensure you have an active internet connection when running the notebooks to allow data retrieval.

Alternatively, you can download the dataset manually from Kaggle:

[Google Stock Market Data](https://www.kaggle.com/datasets/babaksh/googlestock/versions/2)

## Dependencies

The primary dependencies for these notebooks include:

- Python
- Jupyter Notebook
- TensorFlow
- PyTorch
- Pandas
- NumPy
- Matplotlib
- yfinance

These packages can be installed using the `pip install` command as demonstrated in the "Getting Started" section.

## Contributing

Contributions to enhance the functionality or accuracy of the models are welcome. Feel free to fork the repository, make your changes, and submit a pull request.

## Acknowledgments

Special thanks to the open-source community for providing valuable resources and tools that made this project possible.
