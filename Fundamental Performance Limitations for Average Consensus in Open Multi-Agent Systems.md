#### Fundamental  Performance Limitations for Average Consensus in Open Multi-Agent Systems

#### IEEE  Transactions on Automatic Control  2022                          		                                                         粗读                                              



#### 关键词：

multi-agent  systems, Agents and autonomous systems, Cooperative control, Sensor  Networks,Markov processes.



#### 研究内容：

分析了open  multi-agent system，重点关注于算法在恒定规模下open multi-agent system的下限（lower  bounds），其中下限由分析算法的均方误差得出。通过设定knowledge set来定义单个agent的信息。并且在几个模型上进行了实例化演示。



#### 创新点:

利用knowledge  set定义与处理agent的信息，便于进一步在open system中进行信息处理。



#### 主要结论：

#### 研究意义：

为研究与分析open  multi-agent system提供了工具与方法。



#### 重要图表：

##### 1.通过均方误差的期望来获得lower bounds

![image-20220119113927485](C:\Users\LSY\AppData\Roaming\Typora\typora-user-images\image-20220119113927485.png)

##### 2.最优估计

![image-20220119163134017](C:\Users\LSY\AppData\Roaming\Typora\typora-user-images\image-20220119163134017.png)

##### 3.利用单个agent信息评估系统误差

![image-20220119163220290](C:\Users\LSY\AppData\Roaming\Typora\typora-user-images\image-20220119163220290.png)

##### 4.分析单个agent误差

![image-20220119163424202](C:\Users\LSY\AppData\Roaming\Typora\typora-user-images\image-20220119163424202.png)



#### 问题与思考：

1.如何在一个实际的open system中进行性能评估，如何观测lower bounds所需的变量
2.在一个实际系统中，如何满足论文假设条件
3.lower bounds如何评价系统性能指标，以何种方式体现，不同的lower bounds对系统的影响体现在哪些方面。
4.已知算法在某系统的lower bounds后，如何从lower bounds的角度优化算法



#### 备注：

>本次论文为粗读，对于第五章中公式给出部分不是特别熟悉，对于第六章中通过对于模型演示部分看的不是很懂。
