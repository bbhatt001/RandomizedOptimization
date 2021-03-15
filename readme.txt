Data sets:
Pima Indian Diabetes Database
Available at Kaggle 
https://www.kaggle.com/uciml/pima-indians-diabetes-database
Included as diabetes.csv.

Analysis:
1. 4peaks-GA.ipynb contains analysis of the Four Peaks problem.
2. Count_ones_SA.ipynb contains analysis of the Count Ones problem.
3. Knapsack-MIMIC.ipynb contains analysis of the Knapsack problem.
3. diabetes-random-optimization.ipynb contains neural network weights optimization.

Runtime Environment:
All the code was tested on Python 3.7.6. The environment packages are listed in
requirements.txt and may be installed through the following command (not all
may be necessary).

$ pip install -r requirements.txt

The key packages (installed automatically with the above command) are:
matplotlib==3.3.0
numpy==1.18.5
pandas==1.1.0
scikit-learn==0.23.1
six==1.15.0
mlrose==1.3.0

In addition, the neural network weights optimization uses the mlrose_hiive
module with a minor tweak to get the correct fitness curve for randomized hill
climbing with restarts. I include the entire source of this package for
convenience.
