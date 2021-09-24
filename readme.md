# 运行顺序

1. 数据预处理 preprocess
2. 使用P训练Bert分类器(10分类)  train_bert
3. 使用已训练的分类器预测U，并输出RN build_pu_data
4. 使用P和RN训练二类器
5. 使用 Bert分类器 和 二分类器 联合预测 测试集上样本的类别，输出结果至文件joint_predictor

2021DIGIX赛题二基于多模型迁移预训练文章质量判别rank50/250，主要基于baseline，加了一些tricks，仅供参考
