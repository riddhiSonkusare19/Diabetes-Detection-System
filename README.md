🩺 Diabetes Detection System

A responsive and interactive web-based Diabetes Detection System that predicts the likelihood of diabetes in a patient using machine learning. The system takes key medical inputs such as glucose level, blood pressure, BMI, and other health indicators, then communicates with a backend model (via Flask API) to generate an accurate prediction and helpful lifestyle recommendations.

🚀 Features

🧠 Machine Learning Integration: Predicts diabetes probability based on medical data.

💡 Dynamic Frontend: Built with pure HTML, CSS, and JavaScript — no external frameworks required.

📊 Interactive UI:

Displays probability of diabetes with animated progress bar.

Shows personalized recommendations for both positive and negative predictions.

Summarizes patient input in a clear, structured data grid.

⚙️ Backend Ready: Easily integrates with a Flask-based REST API (/api/predict) for real predictions.

🔄 Error Handling & Demo Mode: Works even when backend is offline by using random demo data.

📱 Fully Responsive: Optimized for desktop and mobile screens.

🧩 Tech Stack

Frontend: HTML5, CSS3, JavaScript (Vanilla JS)

Backend (for ML model): Flask (Python) (to be connected separately)

ML Model: Any trained diabetes prediction model (e.g., Logistic Regression, Random Forest, SVM, etc.)

⚙️ How It Works

The user enters patient details such as glucose level, BMI, age, etc.

On submission, the frontend sends the data to the backend API endpoint (/api/predict).

The backend ML model processes the data and returns:

prediction: “Positive” or “Negative”

probability: A value between 0 and 1

The interface updates instantly with:

Prediction result

Probability bar

Personalized health recommendations

Summary of patient inputs

🧠 Future Improvements

Integrate actual ML model trained using the Pima Indians Diabetes Dataset.

Add authentication and user history tracking.

Visualize trends using charts and analytics dashboards.

Deploy on platforms like Render, Vercel, or GitHub Pages.

🧑‍💻 Author

Riddhi Sonkusare
