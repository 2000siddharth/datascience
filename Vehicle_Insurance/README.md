### Health Insurance Cross Sell Prediction
#### Predict Health Insurance Owners' who will be interested in Vehicle Insurance

There is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer.

I am building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

Now, in order to predict, whether the customer would be interested in Vehicle insurance, I have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

### Algorithms used
#### 1. Logistic Regression
The classfier used an 'L2' penalty and achieved the following scores on various metrics:
| Metric | Score |
| ------ | ----- |
| Accuracy | 0.64 |
| F1 score | 0.70 |
| AUC | 0.835 |

#### 2. Random Forests Classifier

| Metric | Score |
| ------ | ----- |
| Accuracy | 0.70 |
| F1 score | 0.74 |
| AUC | 0.859 |
