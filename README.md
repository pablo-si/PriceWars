# Price Wars

This project explores **competitive pricing as a multi-armed bandit problem**. A learner chooses from a fixed set of prices using either **Upper Confidence Bound (UCB)** or **Multiplicative Weights (MW)**, while a competitor selects a myopic best-response price. Customers choose between the two sellers probabilistically, based on their price difference and a price-sensitivity parameter.

The goal is to study how online learning algorithms behave when their pricing decisions influence a competing seller's actions.

**Project files:** [Jupyter notebook](Price-Wars.ipynb) · [Technical report](Report_Price-Wars.pdf)
