# Sign Language Recognition App 

![Capture](https://github.com/user-attachments/assets/5dab1d3f-dab6-4436-af58-bcb4698be6ac)

This repository hosts the Sign Language Recognition App, a powerful tool designed to interpret and recognize sign language gestures. The app leverages machine learning to provide a seamless and efficient experience for users. Below, you will find detailed information about the app's structure, features, and usage.



## Key Features
Real-time Gesture Recognition: Accurately identifies sign language gestures.
Flask Backend: Ensures a lightweight and responsive server-side application.
Machine Learning Integration: Utilizes a Random Forest Regressor to predict and classify gestures.
User-Friendly Interface: Designed to be intuitive for users, regardless of technical expertise.

## Technology Stack
Backend: Flask (Python)
Machine Learning Model: Random Forest Regressor (scikit-learn)
Frontend: HTML, CSS, and JavaScript (for interfacing with users)
Data Handling: Pandas and NumPy (Python)

# Installation
Prerequisites
Python 3.11+
Pip for Python package management
Virtual Environment (optional but recommended)

#Steps
## Clone the repository:

```bash
Copy code
git clone https://github.com/your-username/sign-language-app.git
cd sign-language-app
```

## Set up a virtual environment (optional):

```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```
## Install dependencies:
```bash
pip install -r requirements.txt
Run the Flask app:
```
```bash
python app.py
```
## Dataset
The app is trained using a labeled dataset of sign language gestures. Each sample includes:

Input Features: Key points or characteristics derived from images or sensor data.
Target Output: Corresponding sign language symbols or letters.

## Model Training
The Random Forest Regressor is trained on the preprocessed dataset to learn the relationship between features and their corresponding labels. Here's an overview of the training process:

## Data preprocessing and cleaning

Feature extraction

## Model training using scikit-learn:
```bash
python
from sklearn.ensemble import RandomForestRegressor


model = RandomForestRegressor(n_estimators=100, random_state=42)
model.fit(X_train, y_train)
```

# Usage

Start the Flask server:

```bash
Copy code
python app.py
```

Access the App: Open your browser and go to http://127.0.0.1:5000.

Upload a Gesture: Use the interface to upload images or input gestures.

View Results: The app will display the recognized sign language symbol.


## Contributing
Contributions are welcome! Follow these steps to contribute:

# Fork the repository.

## Create a new branch:
```bash
git checkout -b feature-name
```

## Commit changes and push:
```bash
git add .
git commit -m "Add your message here"
git push origin feature-name
```
Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.

## Contact
For any inquiries or issues:

Email: dukekongo16@example.com
GitHub: https://github.com/poppatheduke

# Enjoy using the Sign Language Recognition App!
