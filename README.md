# Student Performance Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Linear%20Regression-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1RrPrWA2x6KszEReFEerrIZRfcQkKsP4B)

## Overview
Developed a Linear Regression model to predict students’ final exam marks using key academic performance indicators. The project focuses on building a clean, interpretable model with strong predictive capability and realistic output constraints.

## Approach
- Removed non-informative features such as `Student_ID` to eliminate noise  
- Selected only relevant numerical features impacting student performance  
- Trained a Linear Regression model using an 80:20 train-test split  
- Evaluated model performance using MSE, RMSE, and R² score  
- Applied output constraints to ensure predictions remain within the valid range (0–100)  

## Features Used
- Attendance (%)  
- Internal Test 1 (out of 40)  
- Internal Test 2 (out of 40)  
- Assignment Score (out of 10)  
- Daily Study Hours 

Target:
- Final Exam Marks (out of 100)

## Model Performance
- Mean Squared Error (MSE): 21.33  
- Root Mean Squared Error (RMSE): 4.62  
- R² Score: 0.83  

## Results
Achieved an R² score of 0.83, indicating strong predictive performance. The model maintains an average error of approximately ±5 marks and produces consistent, logically aligned predictions across varying input levels.

## How to Run
git clone <your-repository-link>  
cd <repository-folder>  
pip install -r requirements.txt  
python main.py  

## Example Prediction
Input:
- Attendance: 100  
- Internal Test 1: 40  
- Internal Test 2: 38  
- Assignment Score: 10  
- Study Hours: 6  

Output:
- Predicted Final Exam Marks: 95.48  

## Contributing
Contributions are welcome. If you would like to improve this project:

1. Fork the repository  
2. Create a new branch (feature/your-feature-name)  
3. Commit your changes  
4. Push to your fork  
5. Open a Pull Request  

## Support
If you find this project useful, consider giving it a star.

## Author
Ronit Maheshwari  
Computer Science (AI & ML) Student
