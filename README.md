# Calorie-Burnt-Prediction
# Calorie Burnt Prediction

This project aims to predict the number of calories burned during physical activities based on user-specific information.
By leveraging machine learning techniques, the application provides accurate calorie expenditure estimates to assist users in optimizing their fitness routines.

---

## Features

- **User Input:** Collects data such as gender, age, height, weight, exercise duration, heart rate, and body temperature.
- **Prediction Model:** Utilizes a machine learning model to estimate calories burned.
- **Web Interface:** Provides an interactive web application for users to input data and receive predictions.

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Balajiprathipati/Calorie-burnt-prediction.git
cd Calorie-burnt-prediction
```

### 2. Install Dependencies
Ensure you have Python 3.x installed. Install the required packages using:

```bash
pip install -r requirements.txt
```

If requirements.txt is not available, install the dependencies manually:

```bash
pip install pandas numpy scikit-learn flask
```

### 3. Prepare the Dataset
Ensure that the dataset files calories.csv and exercise.csv are placed in the data/ directory.

### 4. Train the Model
Run the Jupyter Notebook to train and save the model:

jupyter notebook notebooks/calorieburntprediction.ipynb
Ensure that the trained model is saved as model.pkl in the models/ directory.

### 5. Run the Application
Start the Flask web application:

```bash
python app.py
```

Open http://127.0.0.1:5000/ in your web browser to use the app.

## Usage

Input Data: Enter your personal and exercise details into the web form.
Get Prediction: Submit the form to receive an estimate of calories burned.
Optimize Workout: Use the feedback to adjust and improve your fitness regimen.

## Project Structure
```bash
Calorie-burnt-prediction/
├── app.py                 # Flask application script
├── data/                  # Directory containing datasets
│   ├── calories.csv
│   └── exercise.csv
├── models/                # Directory for storing trained models
│   └── model.pkl
├── notebooks/             # Jupyter Notebooks for data analysis and model training
│   └── calorieburntprediction.ipynb
├── static/                # Static files (e.g., CSS)
│   └── styles.css
├── templates/             # HTML templates for the web interface
│   ├── index.html
│   └── result.html
└── README.md              # Project documentation
```

### Description of Files
- **app.py** - Flask application script.
- **data/** - Directory containing datasets.
- **models/** - Directory for storing trained models.
- **notebooks/** - Jupyter Notebooks for data analysis and model training.
- **static/** - Static files (e.g., CSS).
- **templates/** - HTML templates for the web interface.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
