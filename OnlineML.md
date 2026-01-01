Online/Incremental Learning: Model is trained incrementally as new data arrives. The model updates itself continuously without needing to retrain from scratch.

- When to use Online
concept drift (data distribution changes over time)
cost effective
faster solution needed

Library: from skLearn import linear_model

Paramters: same as linear regression

Preprocessing: None

- Hyperparameters to tune:
learning_rate

Pseudo Code:
use SGDRegressor from linear_model
use partial_fit() method to train the model incrementally with new data batches


- Some well known libraries for online learning on live data:
River
Vowpal Wabbit

- Disadvantages:
Risky if data is noisy or contains outliers
So data needs to continously be monitored and cleaned
