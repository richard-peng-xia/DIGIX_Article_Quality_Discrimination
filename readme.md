This repository stores the code for 2021 [DIGIX全球校园AI算法精英大赛](https://developer.huawei.com/consumer/cn/activity/digixActivity/digixdetail/201621215957378831?ha_source=skw_sf&ha_sourceId=89000070) 赛题二 基于多模型迁移预训练文章质量判别.

# Run
1. Preprocess the data `preprocess.py`
2. Train Bert Classifier with P (10 categories)  `Train_Bert.py`
3. Use the trained classifier to predict U and output RN  `Build_PU_data.py`
4. Train the binary classifier with P and RN `Train_PU_model.py`
5. Bert classifier and binary classifier are used to predict the categories of samples on the test set and output the results to `submission.csv` `Joint_Predictor.py`
