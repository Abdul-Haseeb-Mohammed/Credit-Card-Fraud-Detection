 <h1>Project Title: Detecting Fraud in Credit Card Transactions</h1>
    <h2>Problem Statement:</h2>
    <p>
        The objective is to detect fraud transactions, there is significant risk faced by credit card companies and customers when a card is lost or stolen. Credit cards do not require user authentication. When a fraud occurs, customers are liable to pay or when customers don’t pay for fraud transactions credit card companies make financial losses. Also, if a credit card company doesn’t detect fraud transactions, they risk customer churn. For the mentioned reasons it's vital to address this problem.
    </p>
    <h2>Proposed Solution:</h2>
    <p>
        The solution proposed is to employ machine learning algorithm for classification of fraud and non-fraud transactions to help predict fraud on new transactions. Also, most transactions are not fraud. And a machine learning algorithm needs transactions of both classes to learn patterns and differentiate between the two classes. However, handling of class imbalance by using under sampling would lead to losing majority of data. And data is vital, so for this reason, oversampling will be done by using SMOTE which creates synthetic data points for the minority class. And finally, different classification algorithms will be employed to assess the performance of these models and choose the best model for the final solution.
    </p>
    <h2>Resources used:</h2>
    <ul>
        <li>Dataset: <a href="https://app.datacamp.com/search/workspace?q=credit+card">https://app.datacamp.com/search/workspace?q=credit+card</a></li>
        <li>SMOTE:
            <ul>
                <li><a href="https://www.analyticsvidhya.com/blog/2020/10/overcoming-class-imbalance-using-smote-techniques/">https://www.analyticsvidhya.com/blog/2020/10/overcoming-class-imbalance-using-smote-techniques/</a></li>
                <li><a href="https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/">https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/</a></li>
            </ul>
        </li>
        <li>Decision Tree Classifier: <a href="https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html">https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html</a></li>
        <li>Random Forest Regression: <a href="https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html">https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html</a></li>
        <li>Logistic Regression: <a href="https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8">https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8</a></li>
        <li>Label Encoding: <a href="https://www.geeksforgeeks.org/ml-label-encoding-of-datasets-in-python/">https://www.geeksforgeeks.org/ml-label-encoding-of-datasets-in-python/</a></li>
        <li>One-Hot Encoding: <a href="https://www.analyticsvidhya.com/blog/2023/12/how-to-do-one-hot-encoding/#:~:text=One%2Dhot%20encoding%20is%20achieved,category%20with%20a%20binary%20column.">https://www.analyticsvidhya.com/blog/2023/12/how-to-do-one-hot-encoding/#:~:text=One%2Dhot%20encoding%20is%20achieved,category%20with%20a%20binary%20column.</a></li>
        <li>Curse of Dimensionality: <a href="https://www.linkedin.com/pulse/what-curse-dimensionality-simplest-explanation-aqsa-zafar/">https://www.linkedin.com/pulse/what-curse-dimensionality-simplest-explanation-aqsa-zafar/</a></li>
    </ul>
