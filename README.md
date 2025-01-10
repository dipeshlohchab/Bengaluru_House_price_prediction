![Screenshot 2025-01-10 094814](https://github.com/user-attachments/assets/a7a94eaa-cdc4-4286-90c3-0a4488407931)


# Bengaluru House Price Prediction

This repository contains a machine learning model and a web application to predict house prices in Bengaluru using linear regression. The project is organized into three main folders: `Client`, `Server`, and `Model`, each serving a specific purpose.

## Features
- **Machine Learning Model**: Linear regression is implemented to analyze the Bengaluru house price dataset and make accurate predictions.
- **Backend**: Flask is used as the backend framework to handle requests and serve the machine learning model.
- **Frontend**: The user interface is built using HTML, CSS, and JavaScript for a responsive and interactive experience.

---

## Project Structure
```
Bengaluru_House_Price_Prediction/
├── Client/
│   ├── app.html                              # HTML for the main interface
│   ├── app.css                               # CSS for styling
│   ├── app.js                                # JavaScript for interactivity
├── Server/
│   ├── server.py                             # Flask application entry point
│   ├── util.py                               # Utility functions for preprocessing
├── Model/
│   ├── Banglore_House_Price_Prediction.ipynb # Jupyter notebook for model training
│   ├── dataset/                              # Folder containing the dataset
│   ├── model.pkl                             # Serialized model file
│   ├── columns.json                          # Metadata for model input
├── requirements.txt                          # Python dependencies
└── README.md                                 # Project documentation
```

---

## Requirements
- Python 3.8+
- Flask
- Pandas
- NumPy
- Scikit-learn

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/dipeshlohchab/Bengaluru_House_Price_Prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Bengaluru_House_Price_Prediction
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Start the Flask server:
   ```bash
   python Server/server.py
   ```

5. Open your browser and load the `Client/app.html` file to access the frontend interface.

---

## Usage
1. Upload your house features (e.g., location, size, number of bedrooms, etc.).
2. The model will predict the approximate price of the house based on the trained dataset.
3. View the results directly on the web interface.

---

## Dataset
The dataset used for training contains house prices in Bengaluru with various features such as location, size, total area, and price. Data preprocessing and cleaning steps are included in the `Model/Banglore_House_Price_Prediction.ipynb` file.

---

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments
- The dataset was collected and preprocessed for this project.
- Flask, Scikit-learn, and other open-source libraries made this project possible.

---

## Author
**Dipesh Lohchab**
- [GitHub Profile](https://github.com/dipeshlohchab)

