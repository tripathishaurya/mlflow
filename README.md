📊 MLflow Fundamentals, Tracking & Hyperparameter Tuning

This repository is a hands-on exploration of MLflow covering everything from basics to real-world experiment tracking.
It demonstrates local and server-based tracking (via DAGsHub), MLflow autologging, hyperparameter tuning, and a clear comparison between MLflow and DVC.

This project is focused on understanding ML experiment management, not just training a model.

🎯 What This Repository Covers

✔ MLflow fundamentals (core concepts)
✔ MLflow autologging
✔ Local experiment tracking
✔ Server-based experiment tracking using DAGsHub
✔ Hyperparameter tuning with MLflow runs
✔ Logging parameters, metrics, and artifacts
✔ Confusion matrix logging
✔ MLflow vs DVC — roles, differences, and when to use what



🧠 Key Concepts Demonstrated
🔹 MLflow Basics

Experiments & runs

Parameters, metrics, and artifacts

Tracking URI

Backend store vs artifact store

🔹 MLflow Autologging

Automatic logging of:

Parameters

Metrics

Models

Reduced boilerplate

Comparison with manual logging

🔹 Server-Based Tracking (DAGsHub)

Remote MLflow tracking server

Centralized experiment management

Team-friendly experiment visibility

Persistent experiment history

🔹 Hyperparameter Tuning

Multiple experiment runs

Parameter comparison across runs

Metric-based evaluation

Selecting the best-performing configuration

🔹 MLflow vs DVC (Conceptual Comparison)
Aspect	MLflow	DVC
Purpose	Experiment tracking	Data & pipeline versioning
Focus	Parameters, metrics, models	Datasets, pipelines
Tracking	Runs & experiments	Git-backed versions
Best Use Case	ML experimentation	Reproducible data workflows
Replacement?	❌ No	❌ No
Works Together?	✅ Yes	✅ Yes

Bottom line:

MLflow tracks experiments.
DVC tracks data & pipelines.
They complement each other — they don’t compete.

▶️ How to Run
1️⃣ Install Dependencies
pip install mlflow scikit-learn matplotlib pandas

2️⃣ Run Experiments
python src/file1.py

3️⃣ Launch MLflow UI (Local)
mlflow ui


Open in browser:

http://127.0.0.1:5000

🌍 Remote Tracking with DAGsHub

Experiments are logged to a remote MLflow server

Useful for:

Collaboration

Resume-worthy projects

Production-style workflows

Tracking URI is configured inside the script.

📌 Why This Project Is Valuable

Shows real ML engineering practices

Covers local + remote tracking

Demonstrates experiment reproducibility

Strong foundation for:

ML Engineer

MLOps

Research workflows

Clean and extendable setup

No toy project nonsense. This is how ML is done properly.

🔮 Possible Extensions

Integrate Optuna for advanced tuning

Combine MLflow + DVC in one pipeline

Add model registry

Deploy trained model using FastAPI

Use cloud-based tracking backend

👨‍💻 Author

Shaurya Tripathi
AI / ML Student
Focused on ML engineering, MLOps, and production-ready systems

📜 License

This project is licensed under the MIT License.
