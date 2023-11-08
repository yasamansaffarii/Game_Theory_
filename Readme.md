Objective: to find ESS for pool population in the presence of BWA attack
Abstract: In the blockchain network of this article, miners can migrate from one pool to another to receive better rewards for their participation in situations where the pools contain attacks. In this article, the theory of evolutionary games was used to investigate the dynamic conditions of the pools in terms of the population of miners. For this purpose, after defining the reward model for the attacking or attacked pools, with the help of the replicator and checking the population growth rate of the pools, the ESSs of the problem were obtained. Also, the criterion of the size of the mining blocks was examined as one of the effective criteria in determining ESSs in order to make a better learning response.

Objective: to find ESS for pool population in the presence of BWA attack
Abstract: In the blockchain network of this article, miners can migrate from one pool to another to receive better rewards for their participation in situations where the pools contain attacks. In this article, the theory of evolutionary games was used to investigate the dynamic conditions of the pools in terms of the population of miners. For this purpose, after defining the reward model for the attacking or attacked pools, with the help of the replicator and checking the population growth rate of the pools, the ESSs of the problem were obtained. Also, the criterion of the size of the mining blocks was examined as one of the effective criteria in determining ESSs in order to make a better learning response.

 

The fitness of all strategies is calculated. Now we calculate the average fitness of all strategies.
 
To produce the next generations, the most important thing is to know the rate or speed of growth of the population ratio of the strategies. For this purpose, we calculate the replicator equation or the growth rate.
 
Now we calculate the new population ratio of each strategy. For this, we need to add the ratio of the current population with the value obtained from the replicator equation. The new ratios will also add up to one. We repeat this evolution process many times over time to check the balance points.
To find fake points or nash, the replicator of all strategies should be set to zero and the ratio of populations should be calculated. To check the stability of the obtained points, you must make sure that if the obtained Nash ratios change by an epsilon, the ratios will return to Nash over time, otherwise it is not stable and ess.
In this article, the strategies are attacking and being attacked, which are actually the characteristics of the pools that miners migrate to. The reward equations of the article are based on blockchain criteria such as hash rate, block size, attack rate, etc. Miners intend to migrate to maximize their reward based on the reward equation. So, in fact, we are dealing with the problem of solving a differential equation problem with respect to the population.
