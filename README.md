# ML-based-diagnosis-cardiac-abnormalities
Project Title
ECG Classification Using Machine Learning and Deep Learning

Overview
This project explores the use of both traditional machine learning algorithms and deep learning models to classify ECG signals. The dataset used is PTB-XL, a large publicly available electrocardiography dataset. The aim is to detect and categorize common heart conditions based on ECG patterns.

Dataset
The PTB-XL dataset is available from PhysioNet. It contains raw ECG waveform data along with diagnostic statements. In this project, only the top 5 most frequent diagnostic classes were considered to simplify the classification task.

Workflow
Data Loading – Metadata and signal paths are loaded from CSV files.
Preprocessing –Extract diagnostic codes
Filter to the top 5 classes
Encode labels for classification
Signal Processing – ECG waveforms are read and prepared for analysis.
Modeling –Machine Learning: Support Vector Machine (SVM) and Random Forest classifiers.
Deep Learning: Convolutional Neural Network (CNN) using TensorFlow/Keras.
Evaluation – Accuracy, precision, recall, and F1 score are computed for all models.

How to Run
Download the PTB-XL dataset from PhysioNet.
Update the base_path in the notebook to point to your dataset location.
Install the required packages:
pip install wfdb numpy pandas matplotlib seaborn scikit-learn tensorflow
Run the notebook step-by-step.

Results
The notebook compares the performance of traditional ML models with a CNN, showing that deep learning can capture complex patterns in ECG data, but also that simpler models still hold value for certain cases.

Author

Ravi Teja
