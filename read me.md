![Graphical user interface, diagram, application Description automatically generated](media/521a012b0698f6c91d1b6a08e838b620.jpeg)

**Website or Mobile APP? That is the question. (Regression)**

For those companies that have both websites and mobile applications, it is a crucial question that which platform they have to invest on more in order to achieve the maximum profit. One way to investigate the question is to check the impact of each one on the behavior of the customers. In this project I use a dataset for a fictional company which sells clothing and provides online services through both website and mobile app. The target in the project is defined as the total amount of money a customer spends yearly and the project is to check the impact of enhancing each platform on total amount of money.

The numerical features in the data set are:

-   Avg. Session Length: Average session of in-store style advice sessions.
-   Time on App: Average time spent on App in minutes
-   Time on Website: Average time spent on Website in minutes
-   Length of Membership: How many years the customer has been a member.

I first go through some Exploratory Data Analysis (EDA) to see if I can find any meaningful relationships between different features. Then different regression models are applied and compared to find the best model. The models that are developed in this project are:

1.  **Linear Regression:** A straight line is fit on the data. This is the simplest regression model with large bias. We will see that in this project, this simplest model works best.
2.  **Decision Tree:** In decision tree regressors, data is split at each node base on the reduction in variance. Decision trees are usually notorious in getting overfit on the training data.
3.  **Random Forest:** This model is a solution to the overfitting issue that decision trees usually have. In random forests, for each node, a feature of a random subset of all features is chosen and by setting a number of estimators, different decision trees are trained based on the data.
4.  **eXtreme Gradient Boost (XGBoost):** In XGBoost, instead of picking from all examples with the same probability, we make it more likely to pick examples that the previously trained trees misclassify.
5.  **Artificial Neural Network (ANN):** Neural networks are the essential components in deep learning. By setting weights and biases in a set of layers of neurons a curve can fit the data and predict the unseen data. Neurons or perceptrons are just simple mathematical functions that act on the input data and the parameters (biases and weights) are adjusted while the model is being trained based on back propagation and gradient descent.

    The metrics for evaluating the performance of models are: Mean Squared Error, Mean Absolute Error, R-squared and residual distribution.
