🎓 PlacePredict — Student Placement Prediction System

Predicts whether a student will be placed based on
CGPA, internships, skills, and communication score
using Logistic Regression. Built with Python, Flask,
and Scikit-learn with a simple web interface.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

DATASET
-------
File     : placement.csv
Features : CGPA, Internships, Skills, Communication
Target   : Placed (1 = Yes, 0 = No)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PROJECT STRUCTURE
-----------------
PlacePredict/
├── app.py           → Flask web application
├── model.py         → Model training script
├── model.pkl        → Saved Logistic Regression model
├── placement.csv    → Dataset
├── requirements.txt → Dependencies
└── templates/
    └── index.html   → Frontend form

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

MODEL
-----
Algorithm : Logistic Regression
Library   : Scikit-learn
Saved As  : model.pkl (via Pickle)

Input Features:
  - CGPA          (e.g. 8.5)
  - Internships   (e.g. 2)
  - Skills        (e.g. 7)
  - Communication (e.g. 8)

Output:
  - 🎉 Student will be Placed
  - ❌ Student will NOT be Placed

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

HOW TO RUN
----------
Step 1 — Install dependencies
   pip install -r requirements.txt

Step 2 — Train the model
   python model.py

Step 3 — Start Flask app
   python app.py

Step 4 — Open browser
   http://127.0.0.1:5000

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

REQUIREMENTS
------------
flask
scikit-learn
pandas
pickle (built-in)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

FUTURE SCOPE
------------
- Add more features (projects, backlogs, etc.)
- Try Random Forest / XGBoost for better accuracy
- Deploy on Render / Railway / Heroku
- Add prediction confidence percentage


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

LICENSE
-------
MIT License — free to use with attribution.

"Predict smarter. Place better." 🎓
