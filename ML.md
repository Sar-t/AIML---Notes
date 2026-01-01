# Types of ML
Based on amount, ML can be categorized into:
- Supervised:

- Unsupervised: 
clustering, dimensionality reduction, association, anomaly detection

- Semi-supervised:

- Based on how model is trained in production:
Batch/Offline Learning: We train on entire dataset at once and then deploy the model. As new data comes in, we retrain the model periodically from scratch(on old + new data). 

Online/Incremental Learning: Model is trained incrementally as new data arrives. The model updates itself continuously without needing to retrain from scratch.

- When to use Online
concept drift (data distribution changes over time)
cost effective
faster solution needed
huge data that cannot fit in memory


