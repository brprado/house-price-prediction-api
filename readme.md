# House Price Prediction API

This project is a Machine Learning API for predicting house prices. It uses the FastAPI framework in Python.

## Installation

1. Clone the repository:

    ```bash
    git clone <repo_url>
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Start the API server:

    ```bash
    uvicorn main:app --reload
    ```

2. Open your web browser and go to `http://localhost:8000/docs` to access the API documentation.

3. Use the provided endpoints to make predictions for house prices.

## API Endpoints

- `POST /predict`: Make a prediction for a house price based on the provided features.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

