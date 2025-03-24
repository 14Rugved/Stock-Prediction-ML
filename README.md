# Stock Market Predictor

The Stock Market Predictor is a Python-based application that uses machine learning to predict stock prices. It utilizes the Keras deep learning library and the Yahoo Finance API to fetch and analyze historical stock data.

## Installation

To run the Stock Market Predictor, you'll need to have the following dependencies installed:

- Python 3.x
- NumPy
- Pandas
- Keras
- Streamlit
- Matplotlib
- yfinance

You can install these dependencies using pip:

```
pip install numpy pandas keras streamlit matplotlib yfinance
```

## Usage

1. Clone the repository or download the `app.py` file.
2. Open a terminal or command prompt and navigate to the directory containing the `app.py` file.
3. Run the application using the following command:

   ```
   streamlit run app.py
   ```

4. The application will open in your default web browser.
5. Enter the stock symbol you want to analyze (e.g., "GOOG" for Google) in the input field.
6. The application will display the historical stock data, moving averages, and the predicted stock price compared to the actual price.

## API

The Stock Market Predictor uses the following APIs:

- **yfinance**: Fetches historical stock data from Yahoo Finance.
- **Keras**: Loads the pre-trained stock prediction model.
- **Streamlit**: Provides the web-based user interface for the application.

## Contributing

If you would like to contribute to the Stock Market Predictor, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

## License

The Stock Market Predictor is licensed under the [MIT License](LICENSE).

## Testing

To run the tests for the Stock Market Predictor, you can use the following command:

```
python -m unittest discover tests
```

This will run all the test cases located in the `tests` directory.