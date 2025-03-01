# LWSC Sensitivity Analysis Project

## 项目概述

本项目主要研究Local Weighted Shapley Chain (LWSC)的敏感性分析。通过使用机器学习方法，特别是CatBoost模型，来分析不同水文因素对LWSC的影响程度。

## 数据说明

项目使用的数据集包含以下主要特征：
- Runoff: 径流量
- P: 降水量
- E: 蒸发量
- Area: 面积
- LWSC: Local Weighted Shapley Chain值（目标变量）

数据存储在 `data/` 目录下：
- `machine_l.csv`: 主要数据文件
- `machine_l.xlsx`: Excel格式的数据文件

## 模型分析

使用CatBoost回归模型进行分析，主要包括：
1. 数据预处理和划分（训练集:测试集 = 8:2）
2. 模型训练与评估
3. SHAP值分析以评估特征重要性

### 模型参数
- iterations: 500
- learning_rate: 0.05
- depth: 3
- loss_function: RMSE

### 评估指标
使用皮尔逊相关系数评估模型性能：
- 训练集相关系数
- 测试集相关系数

## 特征重要性分析

使用SHAP (SHapley Additive exPlanations) 值分析特征重要性：
1. SHAP特征重要性条形图
2. SHAP值分布图

## 环境依赖

主要依赖包：
- pandas
- numpy
- catboost
- scikit-learn
- matplotlib
- shap
- scipy

## 使用说明

1. 克隆项目到本地
2. 安装所需依赖包
3. 运行 `ml.ipynb` 进行分析

## 结果可视化

项目包含多个可视化结果：
1. SHAP特征重要性图
2. SHAP值分布图
3. 相关性分析图

## 联系方式

如有任何问题，请通过以下方式联系：
- Email: [your-email@example.com]
- GitHub Issues 