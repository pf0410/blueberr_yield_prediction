# blueberr_yield_prediction

## 项目介绍
本项目针对野生蓝莓产量预测构建机器学习模型，使用天池公开数据集，通过数据探索分析、特征工程、模型训练与评估，实现高精度产量预测。

## 数据集来源
数据集来源自
Obsie, E. Y., Qu, H., & Drummond, F. (2020).
Wild blueberry yield prediction using a combination of computer simulation and machine learning algorithms.
*Computers and Electronics in Agriculture*, 179, 105844.
https://doi.org/10.1016/j.compag.2020.105844

数据集在天池公开数据集中下载，包含文件：
 - train.csv（训练集）
 - test.csv（测试集）

## 项目流程
1. 数据预处理
2. 描述性统计分析
3. 特征工程
4. 特征标准化
5. 模型训练（随机森林回归）
6. 模型评估
7. 测试集产量预测
8. 其他回归模型与模型集成简单测试

## 分析内容
- 克隆株大小分类对比分析
- 气温与蓝莓生长关系分析
- 降雨量分级分析
- 极端降水情况分析
- 特征相关性热力图
- 预测值分布可视化
- 模型性能评估

## 特征工程
- 删除冗余特征
- 异常值检测与处理
- 新特征构建
- 特征选择
- 特征标准化

## 模型性能
- 验证集 R²：0.8120
- 预测结果分布合理







