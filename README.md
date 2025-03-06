# ML
machine learning codes


# NOTES
1. dt = DecisionTreeClassifier(max_depth=4, random_state=35) - the parameter max_depth controls the maximum depth of the decision tree
**Max_Depth** depends on the number of columns you have

2. Imbalance in target variable\
import - from sklearn.utils.class_weight import compute_sample_weight\
build smaple weights - w_train = compute_sample_weight('balanced', y_train)\
fit into the model - dt.fit(X_train, y_train, sample_weight=w_train)

3. 
