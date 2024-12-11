
# Usage
1. Run the script:
   '''bash
   python knn_iris_classifier.py
   '''
2. Enter the number of neighbors('k') when prompted.
3. View the model's accuracy and balanced accuracy in the console.
4. Input 'sepal.length' and 'petal.length' in the format _value1,value2_ to predict the iris species.

# Example
## Console Interaction:
'''bash
Enter the number of neighbors (k) for KNN: 3
Model Accuracty: 0.96
Balanced Accuracy: 0.95
Enter the sepal.length and petal.length for the iris in the format 'sepal.length petal.length': 5.1,1.8
Predicted Label: Virginica

# Notes
1. Ensure that the input for predictons is numeric and follows the correct format ('value1, value2').
2. Modify the dataset loading path in the script if necessary.

# License
This project is licensed undet the MIT License.

# Author
Developed by krap313@naver.com

## Features
- Hyperparameter tuning for KNN (`k` selection).
- Model training and evaluation.
- Console-based user input for custom predictions.
- Performance metrics: Accuracy and Balanced Accuracy.

## Requirements
Ensure you have the following installed:
- Python 3.x
- pandas
- scikit-learn

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CAU-AID-Class.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CAU-AID-Class
   ```
3. Install required libraries:
   ```bash
   pip install pandas scikit-learn
   ```
4. Ensure the `iris.csv` dataset is available in the project directory.
