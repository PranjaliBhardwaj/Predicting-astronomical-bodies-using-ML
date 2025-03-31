# Predicting-astronomical-bodies-using-ML
<br>
1. Data Exploration and Preparation<br>

Uses LabelEncoder to convert categorical 'class' column to numerical values:<br>

GALAXY → 0<br>

QUASAR → 1<br>

STAR → 2<br>

2. Feature Engineering<br>
Splits data into features (X) and target (y)<br>

Applies StandardScaler to normalize the feature data
<br>
3. Data Visualization<br>
Creates count plots to show class distribution<br>

Uses pairplots to understand feature interdependencies
<br>
Explains the astronomical filters used (u=ultraviolet, g=green, r=red, i=infrared)
<br>
4. Machine Learning Modeling<br>
Imports several classification algorithms:<br>

DecisionTreeClassifier<br>

LogisticRegression<br>
<br>
MultinomialNB
<br>
KNeighborsClassifier
<br>
SVC
<br>
Uses train_test_split (70-30 split)
<br>
Plans to evaluate model performance using accuracy_score
<br>
