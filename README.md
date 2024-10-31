# Time Series Analysis

This repository is dedicated to analyzing and predicting stock prices using advanced deep learning techniques, specifically tailored for time series data. The project primarily focuses on applying and optimizing models such as **LSTM**, **FCN**, **GRU**, and **MLP** to Apple stock data.

## Project Structure

- **Data**: Utilizes historical stock price data for Apple Inc. as a basis for training and evaluation.
- **Models**: Includes LSTM, FCN, GRU, MLP, etc deep learning models for predicting stock prices.
- **Optimization Techniques**: Explores techniques like batch normalization and early stopping to improve model performance.
- **Visualizations**: Provides comparative visualizations of training vs. validation loss, and plots of predictions against actual stock prices for each model.

## Data

The project uses Apple Inc. stock price data. Data pre-processing steps involve:
- Normalizing stock prices to suit deep learning model requirements.
- Creating sliding windows to capture temporal dependencies in stock prices.

## Models Implemented

1. **LSTM (Long Short-Term Memory)**: Suitable for capturing sequential dependencies in time series data.
2. **FCN (Fully Convolutional Network)**: Extracts temporal features using convolutions, helping to generalize over sequential patterns.
3. **GRU (Gated Recurrent Unit)**: Another sequential model with fewer parameters than LSTM, potentially improving training speed.
4. **MLP (Multilayer Perceptron)**: A feed-forward network used as a baseline to gauge the effectiveness of more complex architectures.

Each model is implemented with a baseline configuration before applying advanced optimization techniques.

## Optimizations

To improve model performance, several optimization techniques were applied:
- **Batch Normalization**: Used to stabilize and speed up training.
- **Early Stopping**: Prevents overfitting by monitoring validation loss and stopping training when no improvement is seen.
- **Other Techniques**: Experimented with hyperparameter tuning, such as learning rate adjustments, to optimize results further.

## Comparisons and Observations

Through visualizations and error analysis, comparisons were drawn to evaluate each model's performance. Observations include:
- Cases of model improvement vs. instances of overfitting when different optimizations were applied.
- Documented findings on the best-performing model configurations for accurate stock price prediction.

## Results

Each model’s performance is visualized through:
- **Training vs. Validation Loss**: Showcases the model’s learning progress and instances of overfitting.
- **Prediction vs. Actual Stock Prices**: Evaluates model accuracy on unseen data.

These visualizations provide insights into which model and configuration best suit the stock price prediction task.

## Conclusion

This project provides a foundational understanding of applying deep learning models to time series data, specifically for stock price prediction. The comparisons and documented observations highlight optimal conditions for each model, helping determine the best-performing model setup for real-world applications.
