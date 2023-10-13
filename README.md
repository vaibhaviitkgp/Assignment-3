# Assignment-3

21BT10002_Asgn3: Neural Network Configurations Analysis

This Jupyter notebook delves into the analysis of different neural network configurations, specifically evaluating their performance using cross-validation.

Overview
Initial Setup: The notebook starts off by importing essential Python libraries, namely `numpy` and `pandas`.
Configurations Analysis: The core of the notebook revolves around the analysis of three distinct neural network configurations:
  1. 3 neurons in the hidden layer, learning rate = 0.01
  2. 4 neurons in the hidden layer, learning rate = 0.001
  3. 5 neurons in the hidden layer, learning rate = 0.0001

Each configuration's performance is evaluated using both 5-fold and 10-fold cross-validation. Key metrics like Mean Squared Error (MSE) and its standard deviation are presented.

Key Findings
- The first configuration (3 neurons, learning rate = 0.01) yields the best results with an MSE of approximately 0.00815.
- The other configurations, while having more neurons in the hidden layer, do not significantly outperform or even match the performance of the first configuration.

Conclusion
The notebook concludes that, based on the cross-validation results, the configuration with 3 neurons in the hidden layer and a learning rate of 0.01 is the most optimal among the ones tested.

Usage
To run the notebook:
1. Ensure you have `numpy` and `pandas` installed.
2. Load the notebook in a Jupyter environment.
3. Execute cells in sequence to reproduce the analysis and results.
