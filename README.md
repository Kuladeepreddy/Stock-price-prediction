# Stock Price Prediction with LSTM


## Features

- Utilizes LSTM networks for stock price prediction.
- Fetches historical stock price data from Yahoo Finance.
- Scales and preprocesses the data for model training.
- Visualizes the actual and predicted stock prices using Matplotlib.

## Training and Validation Results

The model is trained for 20 epochs with the Adam optimizer and mean squared error loss. Some key results after training:

- Training Loss (last epoch): ~1.7121e-06
- Validation Loss (last epoch): ~2.0815e-04

## Predictions

The script makes predictions on both the training and testing sets. It then inversely transforms the scaled predictions to obtain actual stock prices.

## Visualization

The results are visualized using Matplotlib, showing actual and predicted stock prices for both the training and testing sets.

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Your contributions are highly welcome!

## License

This project is licensed under the [Your License] - see the LICENSE.md file for details.

## Acknowledgments

- Inspired by the power of deep learning in financial prediction.
- Thanks to TensorFlow and scikit-learn for providing excellent tools for machine learning.

