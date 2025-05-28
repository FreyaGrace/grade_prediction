# 🎓 Student Grade Prediction Model

This project uses a machine learning model to predict student grades based on features such as study time, past scores, and other academic-related inputs. Built with Python, pandas, numpy, and scikit-learn.

## 🧠 How It Works

The model uses **Linear Regression** from scikit-learn to learn relationships between student data and their final grades. The data is shuffled and split into training and testing sets. Once trained, the model can predict grades for new or unseen inputs.

## 📊 Features

- Read and process CSV data with `pandas`
- Train a linear regression model
- Visualize the regression line using `matplotlib`
- Save and load the model using `pickle`
- Evaluate model accuracy

## 🛠️ Technologies Used

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- pickle (for model saving)

## 📁 Project Structure
```bash
grade-prediction/
├── student-data.csv # Dataset
├── student-mat.csv # Dataset
├── import pandas as pd.py # Main ML script
├── requirements.txt # Python dependencies
└── README.md # Project documentation

```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/grade-prediction.git
cd grade-prediction
Install dependencies:
```
```bash
pip install -r requirements.txt
Run the model script:
```
```bash
python grade_model.py
📈 Sample Output
Model accuracy (e.g., Accuracy: 0.87)

Scatter plot with regression line

Predicted vs actual grade comparison
```
# 🔮 Future Improvements
- Add GUI for user inputs

- Include more features (attendance, quiz scores, etc.)

- Explore other regression algorithms

# 📄 License
This project is licensed under the MIT License.
