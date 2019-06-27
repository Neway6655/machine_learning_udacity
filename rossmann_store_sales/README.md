##### 项目使用的软件库

- Pandas: 0.20.3
- pandas-profiling: 1.4.0
- numpy: 1.13.1
- seaborn: 0.9.0
- xgboost: 0.90
- Jupyter Notebook

##### 机器硬件/OS

* CPU: Intel(R) Xeon(R) CPU E5-2650L v3 @ 1.80GHz, 8核
* Memory: 20G
* OS: Linux

##### 训练时间

* 特征筛选使用100个模型，大概需要1天多时间完成所有模型训练
* 模型超参数调优，一共27种组合，只对最优的特征筛选模型进行调优，大概需要不到1天时间完成所有模型的训练

##### 代码说明

* data_exploration.ipynb：训练数据探索和基准模型
* event_feature_extract.ipynb：训练数据事件类特征数据准备
* model_training.ipynb：数据预处理，销售特征数据准备，特征筛选，模型超参数调优
* model_eval.ipynb：模型结果可视化

##### 模型最终提交到Kaggle得分

| Public Score | Private Score |
| ------------ | ------------- |
| 0.11687      | 0.10984       |

