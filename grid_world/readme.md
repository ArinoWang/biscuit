# Grid World

**固定不同的探索率（epsilon）下，sarsa收敛的Q值是不同的**

![gridword_q_sarsa](https://github.com/ArinoWang/biscuit/blob/main/grid_world/epsilons_differ.png)

从图中看出，在*Q学习*中epsilon取值改变，初始状态的最大Q值不变，且收敛于真实值；但在*Sarsa*中epsilon取值改变，初始状态的最大Q值改变，且只有在epsilon较小时其值才收敛于真实值。

