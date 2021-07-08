# Grid World

**固定不同的探索率（epsilon），sarsa收敛的Q值不同**

![gridword_q_sarsa](https://github.com/ArinoWang/biscuit/blob/main/grid_world/epsilons_differ.png)

从图中看出，在Q学习中epsilon取值改变，初始状态的最大Q值是不变的，且收敛于真实值；但在Sarsa中epsilon取值改变，初始状态的最大Q值是改变的，只有在epsilon较小时其值才收敛于真实值。
