# CA-03
### Intro to ML class- Computer Assignment 03 Decision Tree Calssifier Model

_Brief description:_ <br> 
A decision tree classifier model is developed to predict income class using a dataset containing 7 demographic variables. The model is trained, tested, and evaluated for performance. Hyperparameters are optimized through 4 runs to construct the "BEST" tree based on accuracy, followed by visualization and prediction of income for new instance.

_Code explanation:_<br>
Part 1- Data Quality Analysis to handle missing values, outliers and create a data quality report.
Part 2- Build Decision Tree Classifier Model, a "draft" one.
Part 3- Evaluate Performance using confusion matrix, accuracy, precision, recall and F1 score.
Part 4- Tune Decision Tree Performance based on accuracy by iterating through different hyperparameter options and choosing the best one. 4 runs for 4 different hyperparameters (split criteria, min sample leaf, max feature, max depth)
Part 5- Visualize the Best Decision Tree using GraphViz.
Part 6- Conclusion, answer some questions
Part 7- Prediction Using Your "trained" Decision Tree Model. Inputing the given "new" individual demographic profile to predict its income category.
 

_Software:_<br>
* Python 3.x
* pandas
* matplotlib.pyplot
* seaborn
* numpy
* time
* LabelEncoder from sklearn.preprocessing
* DecisionTreeClassifier, plot_tree from sklearn.tree
* pydotplus
* confusion_matrix, accuracy_score, precision_score, recall_score, f1_score, roc_curve, auc from sklearn.metrics
* HandlerLine2D from matplotlib.legend_handler 

_Data set:_<br>
The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. Target classes- 2 ('>50K' and '<=50k') [labels:1,0]. 48,842 rows. The path for the data source: "https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true".


_Instructions:_<br>
Download the code file and run all in order. The Jupyter Notebook contains the entire code and logic for the decision tree classifier, as well as answers for the questions. Before running the program make sure you download the required package and import the needed libraries.

_Authors:_ <br>
Riley Nickel, Taleen Barake, Lior Ben David
