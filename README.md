LightGBM with Hyperparameter Tuning for IoT Intrusion Detection

📌 Project Overview

This project applies Light Gradient Boosting Machine (LightGBM) to the CIC-IoT 2022 dataset for analyzing IoT device behavior and detecting anomalies.
We compare Random Search and Bayesian Optimization for hyperparameter tuning to enhance model accuracy and efficiency.

🔑 Key Objectives

Preprocess and clean IoT network traffic data.
Extract meaningful features for device behavior and intrusion detection.
Apply LightGBM for classification tasks.
Optimize hyperparameters using Random Search and Bayes Search.
Compare performance in terms of accuracy, precision, recall, F1-score, and runtime.

📂 Dataset (CIC-IoT 2022)

Collected using Wireshark & dump-cap.
Includes multiple experiments: Power, Idle, Interactions, Scenarios, Active, Attacks.
48 extracted features (packet size, protocols, traffic timing, etc.).
Challenges: large volume, missing values, high class imbalance.

⚙️ Methodology

Preprocessing: Handle missing values & balance data.
Modeling: Train LightGBM for IoT traffic classification.

    Hyperparameter Tuning:
    Random Search: Efficient for large spaces.
    Bayes Search: Probabilistic, faster convergence.
    Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix.

📊 Results

Both tuning methods achieved high accuracy.
Bayesian Search: More accurate & ~25% faster.
Random Search: Still effective, simpler to implement.

✅ Conclusion

LightGBM is highly effective for IoT intrusion detection.
Hyperparameter tuning is critical for maximizing performance.
Bayesian Optimization is preferred due to higher accuracy and lower runtime.
