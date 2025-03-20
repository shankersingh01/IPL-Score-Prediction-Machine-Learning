# IPL Score Prediction Machine Learning

## Live Demo
🔴 Check out the live application: [IPL Score Predictor](https://shankersingh01-ipl-score-prediction-machine-learning-app-zewyqk.streamlit.app/)

## Overview
This project is a machine learning application that predicts IPL (Indian Premier League) cricket match scores. Using historical IPL data and advanced machine learning algorithms, the model predicts the likely score range for a match based on the batting and bowling teams.

## Features
- Real-time score prediction
- Interactive user interface built with Streamlit
- Support for all IPL teams
- Prediction with confidence intervals
- Easy-to-use team selection interface

## Tech Stack
- Python 3.x
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Machine Learning (Random Forest Regressor)

## Local Setup
1. Clone the repository
```bash
git clone https://github.com/shankersingh01/IPL-Score-Prediction-Machine-Learning.git
cd IPL-Score-Prediction-Machine-Learning
```

2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run the application
```bash
streamlit run app.py
```

## Model Information
- Algorithm: Random Forest Regressor
- Features: Batting Team, Bowling Team
- Target: Match Score
- Model File: `ml_model_compressed.pkl`

## Project Structure
```
├── app.py                      # Main Streamlit application
├── ml_model_compressed.pkl     # Trained machine learning model
├── requirements.txt            # Project dependencies
└── README.md                  # Project documentation
```

## Usage
1. Open the application (either local or live version)
2. Select the batting team from the dropdown
3. Select the bowling team from the dropdown
4. Click on "Predict Score" button
5. View the predicted score range

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is open source and available under the [MIT License](LICENSE).

## Contact
Created by [@shankersingh01](https://github.com/shankersingh01) - feel free to contact me! 