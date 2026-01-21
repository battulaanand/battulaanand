🌍 ExoHabit AI

ExoHabit AI is a web-based application that predicts the habitability of exoplanets using machine learning algorithms. The system leverages scientific features of planets to provide habitability scores and explanations, making it easier for researchers and enthusiasts to understand the potential of exoplanets to support life.

🔹 Features

Habitability Prediction: Predicts whether a given exoplanet is potentially habitable.

Explainable AI: Uses SHAP (SHapley Additive exPlanations) to provide visual explanations for model predictions.

Database Integration: Stores input and prediction results in a SQLite database.

Interactive Web Interface: Users can input exoplanet parameters and get instant predictions.

Visualizations: Generates charts and graphs to interpret model outputs.

🌐 Live Demo

You can access the live web application online at:

ExoHabit AI - Live Demo

Replace the above link with your actual Render deployment URL once deployed.

🛠 Technologies Used

Programming Language: Python

Web Framework: Flask

Machine Learning: Scikit-learn, SHAP

Data Handling: NumPy, Pandas

Visualization: Matplotlib, Seaborn

Database: SQLite

Frontend: HTML, CSS, JavaScript

💻 Installation

Clone the repository:

git clone <your-repo-url>
cd ExoHabitAI


Create a virtual environment:

python -m venv venv


Activate the virtual environment:

Windows: venv\Scripts\activate

Mac/Linux: source venv/bin/activate

Install the required dependencies:

pip install -r requirements.txt


Run the Flask application:

python app.py


Open your browser and go to:

http://127.0.0.1:5000

📂 Folder Structure
ExoHabitAI/
│
├── backend/
│   ├── habitability_model.pkl      # Trained ML model
│   ├── scaler.pkl                  # Scaler for preprocessing
│   └── habitability.db             # SQLite database
│
├── static/                         # CSS and frontend assets
├── templates/                      # HTML templates
├── app.py                          # Flask application
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation

🚀 Usage

Open the web application in your browser.

Enter the exoplanet parameters in the input form.

Click Predict to get the habitability result.

View the SHAP visualizations for model explanation.

The input and predictions are automatically stored in the database.

📊 Model Explanation

ExoHabit AI uses machine learning to classify exoplanets based on their features. The system also provides SHAP plots to visualize the impact of each feature on the prediction. This ensures transparency and interpretability of the AI model.

✨ Author

Anand Joel
