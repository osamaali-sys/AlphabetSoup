# AlphabetSoup

### OBJECTIVE

We are looking into a real life data to build our own machine learning model that will be able to predict the success of a venture paid by Alphabet soup.

### RESOURCES

python, jupyter notebook, TensorFlow, Machine learning

### RESULT

In this challange we had over 34,000 rows in our data file, initially we cleaned our data by focusing on few points;

1. remove any columns which are not part of our target input

2. remove any outliers and bucket any rare categories

3. standardize numerical data by using standard scaler

We used Random Forest as our algorithm. 

hidden_nodes_layer1 =  24, hidden_nodes_layer2 = 10, hidden_nodes_layer3 = 6

I tried to increase n_estimators, change verbose between 0-2, added and removed hidden layers. i was not able to increase accuracy to over 75%

I wouldve used linear regression next, because SVM was taking too long to claculate prediction.

