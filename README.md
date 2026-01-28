# Human Activity Recognition using SVM

## Project Overview
This project builds a *Human Activity Recognition (HAR)* system using *Support Vector Machine (SVM)* to classify daily activities from smartphone sensor data.  
It predicts activities like *Walking, Sitting, Standing, and Laying*, similar to fitness trackers and wearable devices.

---

## Dataset
- *UCI Human Activity Recognition Dataset*
- Accelerometer & gyroscope based features
- 561 engineered features
- 6 activity classes:
  - WALKING  
  - WALKING_UPSTAIRS  
  - WALKING_DOWNSTAIRS  
  - SITTING  
  - STANDING  
  - LAYING

## Approach
- Feature scaling using *StandardScaler*
- Model training using *Linear SVM*
- Evaluation with accuracy, classification report, and confusion matrix
- PCA visualization for activity separation
- User input simulation on unseen test samples

## Results
- *Accuracy:* ~96%
- Linear SVM performed better than RBF after scaling
- Expected overlap between Sitting and Standing activities

## Tech Stack
Python, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

---
##  Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/tanishaasaklani/human-activity-recognition.git
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
3. Open notebook:
   ```bash
   jupyter notebook svm_har.ipynb

## 📬 Contact
Created by **Tanisha Saklani** - MCA AI & DS Student.
Open to feedback!
