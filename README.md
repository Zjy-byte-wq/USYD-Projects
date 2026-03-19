# USYD-Projects
本文针对自动驾驶交互场景中强化学习安全决策问题，提出 DiStaK 分布式 Stackelberg 强化学习框架，将多车辆交互建模为领导者—跟随者的双层博弈决策过程，并将每辆车视为具备自主决策能力的 智能体（AI Agent）。在离散实现中提出 DiStaK-C51，利用 C51 分布式强化学习预测安全代价分布，并通过 CDF 阈值构建概率约束的安全动作集合。同时引入 Top-K 检索—精炼机制 提升决策效率，并通过自适应拉格朗日乘子实现风险约束控制。实验在 merge 与 roundabout 自动驾驶基准环境上表明，该方法在保持任务性能与训练稳定性的同时显著提升安全指标，并具备向多车交通 多智能体（Multi-Agent）系统 扩展的潜力。

源码位置：https://www.dropbox.com/scl/fo/cggn0vzjfsq8ycgk8mo2d/AOoeGxVFO9R46yTX_Kiucvk?rlkey=9ujvhpsvr0iqdzqv1o441qacn&st=ek8dylyb&dl=0

论文位置：https://ieeexplore.ieee.org/document/11368873
