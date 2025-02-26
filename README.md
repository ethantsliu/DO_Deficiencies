# The Consequences of Communication Deficiencies on Distributed Optimization Networks
**Abstract:**

There are many different types of online networks, one of which is multi-agent systems. A multi-agent system or network consists of multiple decision-making agents which interact in some environment to achieve a certain goal. Agents or nodes may be collaborative or antagonistic in achieving their goals. In distributed optimization of multi-agent systems, nodes cooperate to
minimize a global function which is a sum of agents’ local objective functions. Each agent has a connection or edge with some or all other agents. These systems occur in settings such as client-server architecture, machine learning, power systems, and smart manufacturing. Metaheuristic algorithms such as distributed stochastic gradient descent (D-SGD) and consensus-based optimization (CBO) are commonly used in distributed optimization in order to optimize the global function. However, some networks may have irregularities that affect performance: 1) stragglers,
in which nodes inconsistently optimize the local function due to subpar computation power, and 2) faltering edges, where agents or nodes may have issues communicating due to device or network compatibility. We term these communication deficiencies and study them in various convex and non-convex multivariable benchmark function settings. We conclude that the two algorithms perform equally for benchmark functions in the non-convex setting. However, in all other settings, including the convex setting and all settings incorporating both types of communication deficiencies, CBO outperforms D-SGD.


[Read the full paper here](https://drive.google.com/file/d/1YiolxDXJc1WDFXqE7kEQ0uNn4xKYhgSY/view?usp=sharing)
