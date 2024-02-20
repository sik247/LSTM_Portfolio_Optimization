# LSTM-Based Portfolio Optimization for Mirae Asset

This project leverages the power of Long Short-Term Memory (LSTM) neural networks to optimize investment allocations within the Mirae Asset portfolio. By analyzing historical stock data, including daily opening, high, low, closing prices, and trading volumes, the model predicts future price movements to determine the optimal investment weights for each stock, aiming for an effective portfolio composition that maximizes returns and minimizes risk.

## Project Highlights

- **Data-Driven Decision Making**: Utilizes extensive financial datasets to train the LSTM model, ensuring decisions are grounded in historical trends and patterns.
- **Advanced Machine Learning**: Implements an LSTM neural network, showcasing deep learning's potential in financial analyses and investment strategy development.
- **Customizable Portfolio Strategy**: Allows for dynamic adjustment of investment strategies based on predicted market movements, demonstrating flexibility in financial planning and asset management.

## Getting Started

Follow these instructions to clone and run the project locally for development and testing purposes.

### Prerequisites

- Python 3.6+
- TensorFlow 2.x
- Pandas, NumPy, Matplotlib, Scikit-Learn
- Jupyter Notebook or any Python IDE

### Setup and Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/mirae-asset-lstm-portfolio.git
    ```

2. Install the required Python packages:
    ```bash
    pip install tensorflow pandas numpy matplotlib scikit-learn jupyter
    ```

3. Open the project in Jupyter Notebook or your preferred IDE and run the notebooks/code.

## Model Training and Evaluation

- The LSTM model is trained on a dataset split into training, validation, and test sets to ensure robustness and avoid overfitting.
- EarlyStopping and ModelCheckpoint callbacks are used to monitor validation loss and save the best model.
- The project includes a comprehensive analysis of the model's performance, with visualizations of predicted vs. actual prices and portfolio returns.

## Built With

- **TensorFlow & Keras**: For creating and training the LSTM model.
- **Pandas & NumPy**: For data manipulation and numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
