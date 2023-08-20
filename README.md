# COMP8260
This is for ANU COMP 8260 Tutorial 4

2023.8.11 First Meeting 

Chinese Version
第一次小组会议在8.11第一次tutorial上，这次讨论主要明确了小组应该选择的问题，问题主要聚焦于解决城市交通的问题。这次会议由Austin主持，Haotian, ZhuoKun和YuLin参加会议。每位小组成员都对这次会议发表自己的看法。但总体上是对这次主题有一个大致的看法。这次会议为每位组员定下了任务，选择自己关注领域的文献与数据资料，进行分析与总结，然后在下一次的tutorial上进行发言并选择1到2个topic进行仔细的讨论。

小组成员签名：Austin Lee（u7551070） Haotian Liang（u7588736） Zhuokun Chen（u7588775） Yulin Zheng（u7588674）

*English Version*
The first group meeting took place during the tutorial on August 11th. During this discussion, we mainly clarified the issue that our group should address, with a primary focus on solving urban transportation problems. This meeting was chaired by Austin, with Haotian, ZhuoKun, and YuLin in attendance. Each group member expressed their views on the meeting. Overall, there was a general consensus on the main topic. In this meeting, tasks were assigned to each member, directing them to choose literature and data related to their area of interest, analyze and summarize, and then present their findings in the next tutorial. They will also choose 1 to 2 topics for a more detailed discussion.

Group members signatures:
Austin Lee (u7551070)
Haotian Liang (u7588736)
Zhuokun Chen (u7588775)
Yulin Zheng (u7588674)

2023.8.18 Second Meeting 

Chinese Version
第二次小组作业主要确定了这次小组作业讲要以哪种方式呈现，是以程序还是模拟的方式呈现。这个问题将继续在下一次小组会议中被讨论。但我们小组认为模拟这一方法可能更容易实现，因为大家都具有统计学背景，用量化的方式来实现我们的解决方案会更加直观和具体。我们选择的细分主题是智能道路管理系统。我们小组其中一个较为成熟的解决方案是，采用BP神经网络的方法，利用大数据加机器学习去对这个系统做出一个优化。举个例子，我们可能会采用早高峰时期道路的使用情况作为因变量。将安全情况，路口红绿灯的通过情况，道路的出现交通事故的概率等这些数据作为自变量，去研究这些因变量与自变量的关系，并且研究每个自变量对于因变量的影响权重。并且利用机器学习的方法，让AI寻找最影响因变量的自变量。这样能极大程度的规避人类线性思维的局限性。举个例子，道路出现交通事故能够很直观的反应道路的利用情况-堵车。但是，对于机器来说，道路出现事故固然是一个在统计学上一个很重要的影响因素，但是，在机器成百上千次的模拟过程中，它也许会发现人行横道红绿灯的时间设置不合理导致行人闯红灯才是道路利用率低的另一个主要原因。这是单纯通过统计学的分析所不能达到的。
但我们组仍旧保留了另一个用双重差分法分析的可能性。我们在下一周将进一步评估这两种方法的可行性。因此，这一周的任务是去寻找尽可能多的数据来为后续的模型选择做铺垫，以及对这些模型的理解要更加深入。

小组成员签名：Austin Lee（u7551070） Haotian Liang（u7588736） Zhuokun Chen（u7588775） Yulin Zheng（u7588674）

*English Version*
The second group assignment mainly determined how we should present our project, whether through programming or simulation. This issue will continue to be discussed in the next group meeting. However, our group believes that the simulation method might be more feasible because all of us have a background in statistics. Using a quantitative approach to implement our solution would be more intuitive and concrete. We chose the subtopic of an intelligent road management system.
One of the more mature solutions our group has considered involves using the BP neural network method, harnessing big data and machine learning to optimize this system. For instance, we might use the road usage during peak morning hours as the dependent variable. Safety conditions, traffic light passage at intersections, and the probability of accidents occurring on the road would be the independent variables. We aim to study the relationship between these dependent and independent variables, and also to research the weight of each independent variable's impact on the dependent variable. Additionally, using machine learning, we would have AI identify the most influential independent variables. This approach would greatly avoid the limitations of human linear thinking. As an example, a road accident can directly reflect the condition of the road, such as congestion. However, while an accident is a significant statistical factor, through hundreds or thousands of machine simulations, it might be discovered that the unreasonable timing of pedestrian traffic lights leading to jaywalking could be another major reason for low road usage. This is something that pure statistical analysis might miss.
However, we are still considering the possibility of using the Difference-in-Differences (DiD) analytical method. In the coming week, we will further evaluate the feasibility of both methods. Therefore, this week's task is to find as much data as possible to lay the foundation for subsequent model selection and to deepen our understanding of these models.

Group members signatures:
Austin Lee (u7551070)
Haotian Liang (u7588736)
Zhuokun Chen (u7588775)
Yulin Zheng (u7588674)

