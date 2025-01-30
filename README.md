Air Quality Classification Program
This repository contains an Air Quality Classification Program developed using the Support Vector Machine (SVM) method with GridSearch CV hyperparameter optimization. The project is designed to classify air quality levels based on given input data, improving accuracy through optimized model parameters.

🚀 Features
Classification Model Optimization: Utilizes GridSearchCV to find the best hyperparameters for the SVM model.
Performance Evaluation: Displays confusion matrix and model metrics (precision, recall, f1-score).
User Input Handling: Allows users to input category numbers and receive relevant classification data.
Excel-Based System Display: Processes classification results and organizes them into an Excel spreadsheet.
Python-Based System Display: Outputs classification results in a structured text format.

📊 Model Performance
Best Parameters: { 'kernel': 'linear', 'degree': 3, 'C': 1000 }
Best Score: 0.9999533842126422

🛠️ Technologies Used
Python
Scikit-Learn (Support Vector Machine, GridSearchCV)
Pandas
Matplotlib

📷 Screenshots

🔧 How to Run
Clone this repository:
bash
Copy
Edit
git clone https://github.com/siskamjn/Air-Quality-Classification.git
cd Air-Quality-Classification
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Run the classification script:
bash
Copy
Edit
python classify_air_quality.py

📌 Future Improvements
Expand dataset for better generalization.
Integrate real-time air quality data sources.
Develop a web-based interface for user interaction.
