# Transaction-Fraud-Detection

It's critical for credit card firms to be able to spot fraudulent credit card transactions so that customers aren't charged for things they didn't buy. With Credit Card Anomaly Detection, this project aims to demonstrate the modeling of a data set using Algorithmic machine learning. Anomaly detection is critical because it may not only  be used to detect fraud in bank transactions but also discover faults in manufacturing products,etc.  and even find outliers in a dataset. Our objective here is to detect 100% of the fraudulent transactions. This model is then used to recognize whether a new transaction is fraudulent or not. The challenging part in anomaly detection is that its dataset is highly unbalanced, that is the anomaly occurs around 1% of the total instances in the dataset.

## Approach
There are 3 potential approaches to this problem-
1. <b>Supervised Learning Problem</b>: Fitting several models to the dataset in order to categorize it.
2. <b>Semi-Supervised Learning Problem</b>: Any data points outside of this domain are anomalies, so we only map the right data.
3. <b>Unsupervised Learning Problem</b>: Isolate the fraud points from proper transactions without using labels.

Despite the fact that this dataset has labels, we are going to use this notebook to test multiple anomaly detection algorithms and then use the labels to see if we accurately categorized all of the anomalies.

## Dataset Description
Our Dataset - Credit card Dataset - https://www.kaggle.com/shayannaveed/credit-card-fraud-detection
- The dataset covers credit card transactions done by European cardholders. 
- This dataset contains 284,807 transactions, 492 of which were fraudulent.
- The Main Component Analysis yielded 28 characteristics, all of which are principal components. All of the characteristics' numerical values are contained in the dataset.
- The only attributes that PCA does not transform are 'Time' and 'Amount.' The 'Time' feature contains the number of seconds that have passed between each transaction in the dataset. The transaction amount is stored in the 'Amount' feature.
- Another characteristic is 'Class,' which determines if credit card activity is fraudulent or not; if the Class value is 1, the credit card activity is fraudulent; if the Class value is 0, the credit card activity is not fraudulent.
