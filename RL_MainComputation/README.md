<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: RL_MainComputation

Published in: A leveraged investment strategy using Deep Reinforcement Learning

Description: Trains the neural network. The input values are configured in net_config.json. Additionaly, the target drawdown 'D_target' can be set in nnagent.py in the function loss_function8. To run the code, open the command line and enter first 'python main.py --mode=generate --repeat=1' and then 'python main.py --mode=train --processes=1'. The output is then located in the 'train_package'.

The basis for the code was provided by Z. Jiang and can be found here: https://github.com/ZhengyaoJiang/PGPortfolio/blob/master Note that the command 'python main.py --mode=download_data' used to download data from Poloniex, but may not work anymore. A database is provided in the 'database' folder, to allow to replicate the experiments in the Thesis and do other experiments in the time range '01.07.2015 - 31.10.2018'. The database is in the rar format and needs to be extracted before running the code."

Keywords: reinforcement learning, neural network, machine learning, portfolio management, cryptocurrency

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
- D_target - target drawdown

```
