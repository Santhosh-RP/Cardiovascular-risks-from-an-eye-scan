Project Title: Cardiovascular Risk Prediction from Eye Scans
Objective
The primary objective of this project is to develop a deep learning model capable of predicting cardiovascular risk from retinal images. By leveraging non-invasive retinal scans, the model aims to provide an early indication of cardiovascular issues, potentially aiding in timely diagnosis and treatment.


![images (1)](https://github.com/user-attachments/assets/ce4d0b09-bb09-4242-8959-6cf4d4feb40a)


Background
Cardiovascular diseases (CVDs) are a leading cause of mortality worldwide. Early detection and management are crucial to reducing the risk and severity of these diseases. Traditional methods for assessing cardiovascular risk often involve invasive procedures and expensive tests. Recent advancements in medical imaging and deep learning have opened new avenues for non-invasive diagnostics. This project explores the potential of using retinal images to predict cardiovascular risk, capitalizing on the interconnected nature of vascular health throughout the body.

Methodology
Data Collection:

Retinal images and corresponding cardiovascular risk labels were sourced from publicly available medical datasets.
Data is stored in the data/raw directory.
Data Preprocessing:

Images are resized, normalized, and augmented to improve model generalization.
Processed data is saved in the data/processed directory.
Preprocessing scripts are available in the src/data_preprocessing.py and notebooks/data_preprocessing.ipynb.
Model Architecture:

A convolutional neural network (CNN) is designed to extract features from the retinal images.
The model architecture is defined in src/model.py.
Architecture visualization is available in models/model_architecture.png.
Training:

The model is trained on the processed retinal images with corresponding labels.
Training scripts are available in src/train.py and notebooks/model_training.ipynb.
The trained model is saved as models/trained_model.h5.
Evaluation:

Model performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.
Evaluation scripts are available in src/evaluate.py and notebooks/model_evaluation.ipynb.
Results are stored in the results directory.
Prediction:

The trained model can be used to predict cardiovascular risk from new retinal images.
Example prediction scripts are provided in the README.md.
Results
Performance Metrics: Detailed evaluation metrics are available in results/evaluation_metrics.txt.
Visualizations: Example predictions and model performance plots are stored in the results directory.

![Screenshot (400)](https://github.com/Santhosh-RP/Cardiovascular-risks-from-an-eye-scan/assets/109569208/b3c26217-df2f-4659-a296-a5ab86a94375)
![Screenshot (401)](https://github.com/Santhosh-RP/Cardiovascular-risks-from-an-eye-scan/assets/109569208/6c1cda12-bae2-43f5-aaa7-cf549a01bb40)
![Screenshot (402)](https://github.com/Santhosh-RP/Cardiovascular-risks-from-an-eye-scan/assets/109569208/8c573a8e-395c-43f1-b55a-5ad37c990912)




