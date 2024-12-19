<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: RL_MainComputation

Published in: 'A leveraged investment strategy using Deep Reinforcement Learning'

Description: "Trains the neural network. The input values are configured in net_config.json.

The basis for the code was provided by Z. Jiang and can be found here: 

'https: //github.com/ZhengyaoJiang/PGPortfolio/blob/master'

Keywords: 'reinforcement learning, neural network, machine learning, portfolio management, cryptocurrency'

Author: Ilyas Agakishiev

See also: RL_Experiment1Performance, RL_Experiment2Performance

Submitted: 23.04.2019

Input: 

- steps: Number of training iterations in the initial training period.

- learning_rate: Learning rate for (Adam) optimizer.

- batch_size: mini-batch size

- buffer_biased: Geometric distribution parameter when selecting online training sample batches.

- window_size: Number of time periods in the input tensor.

- global_period: Time period in seconds. Can be set to 300 (5 minutes), 900 (15 minutes), 1800 (30 minutes), 3600 (1 hour).

- start_date: First day of training period.

- end_date: Last day of test period.

- test_portion: Share of data used for test set.

- trading_consumption: Fee for buying and selling coins.

- rolling_training_steps: Number of training iterations for each additional data point during online learning.

```
