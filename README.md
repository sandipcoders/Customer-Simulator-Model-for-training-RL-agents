# Customer-Simulator-Model-for-training-RL-agents
Several simulator models were developed using machine learning techniques on the
Dunnhumby-The Complete Journey dataset obtained from Kaggle. These models in-
cluded predicting the next time a customer will visit, determining what a customer
is likely to purchase next, identifying the discounts needed to retain a customer, and
forecasting the revenue generated from a customer after offering discounts.
To simulate the effect of an unknown coupon discount percentage (action), a model
was developed to predict the customer’s next state and reward value. TensorFlow was
used to train RL models using this customer simulator environment. The RL models
were trained to learn the optimal policy based on the historical dataset. From this
optimal policy, RL determined the best action for unknown data in the test dataset.
Additionally, the customer simulator was used to predict the reward value, which was
compared to the actual reward value of the test data to evaluate the RL model’s
performance. The RL model’s effectiveness in determining the optimal action was
assessed by measuring the accuracy of the predicted reward values against the actual
reward values of the test datase
