# ml-learn
Machine Learning Exercises

### Terms
- Attribute = A data type like "mileage"  
- Feature = An attribute and its value.  ie. mileage=15000
- Label = The desired solution for a collection of Features.
- Supervised Learning = The training set contains desired solutions.
- Classification = A ML technique where you train the system to associate a set of Features with a specific Class.
- Regression = A ML technique where you train the system to predict a numeric value from a set of input Features.
- Unsupervised Learning = The training data is unlabelled and the system attempts to learn without a teacher.
- Anomaly Detection = An unsupervised learning task that is used to identify outliers.
- Novelty Detection = Similar to anomaly detection.  Used to detect new instances that look different from all instances in the training set.
- Dimensionality Reduction = Simplify the data without losing too much information.  One way to do this is to merge several correlated features into one.
- Association Rule Learning = Discover interesting relationships between attributes.
- Semisupervised Learning = A system where only some of the training data is labeled.
- Reinforcement Learning = The learning system, called an agent, observes the environment and peforms actions.  The result of the action will be to earn rewards or incur penalties.  It uses these rewards to learn the best strategy.
- Batch/Offline Learning = The system is trained offline and then run.  To incorporate new information, the system must be retrained.
- Online Learning = System learns by taking small training batches and learning incrementally.
- Learning Rate = How fast a learning system adapts to changing data.  High learning rate means that it adapts quickly to new data but also forgets the old data quickly.  A lower learning rate means that the system will have more inertial and will adapt to change less quickly.
- Instance-Based Learning = The system learns the examples by heart and then uses a similarity measure to compare.
- Model=Based Learning = Use a model to make predictions.  A fitness function is used to determine the quality of the prediction and adjust the values of the model.
- Sampling Noise = Small training sets can lead to nonrepresentative data.
- Sampling Bias - The training data has a bias that leads to incorrect results.
- Feature Selection = Selecting the most useful features amongst the existing features.
- Feature Extraction = Combines exsting feature(s) to produce a nore useful one.
- Feature Engineering = Uses Feature Selection, Feature Extraction and Creating new features by gathering new data to get a good set of features to train on.
- Overfitting = The model performs well on the training data, but does not generalize well.
- Regularization = Constraining the model to make it simpler to reduce the risk of overfitting.
- Hyperparameter = A parameter of the learning system, not the model that controls the amount of regularization.
- Underfitting = When your model is too simple to learn the structure of the data.
