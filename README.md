# Churn Prediction Project1
live at; https://bank-churn-js-ai.streamlit.app/
This project is a machine learning application that predicts customer churn for a bank. The model uses various customer attributes to predict whether a customer will exit the bank.

## Project Structure

## Files

- `Churn_Modelling.csv`: The dataset used for training and testing the model.
- `experments.ipynb`: Jupyter notebook containing the experiments and model training process.
- `label_encoder_gender.pkl`: Pre-trained label encoder for the gender feature.
- `logs/`: Directory containing logs of model training.
- `main.py`: Main script for the Streamlit web application.
- `model.h5`: Trained machine learning model.
- `onehot_encoder_geo.pkl`: Pre-trained one-hot encoder for the geography feature.
- `pyenv/`: Python virtual environment directory.
- `requirements.txt`: List of required Python packages.
- `scaler.pkl`: Pre-trained scaler for feature scaling.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/churn-prediction.git
    cd churn-prediction
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv pyenv
    source pyenv/Scripts/activate  # On Windows
    source pyenv/bin/activate      # On Unix or MacOS
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run main.py
    ```

2. Open your web browser and go to `http://localhost:8501` to interact with the application.

## Features

- Input customer attributes such as age, balance, credit score, estimated salary, tenure, number of products, credit card status, and active member status.
- Predict whether a customer will churn based on the input attributes.
- One-hot encoding for the geography feature.
- Scaled input features for better model performance.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [scikit-learn](https://scikit-learn.org/)
- [pandas](https://pandas.pydata.org/)
- [TensorFlow](https://www.tensorflow.org/)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
