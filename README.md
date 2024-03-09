# Out-of-distribution Detection with Implicit Outlier Transformation --Mindspore

[Out-of-distribution Detection with Implicit Outlier Transformation (ICLR 2023)](https://openreview.net/forum?id=hdghx6wbGuD)

Qizhou Wang, Junjie Ye, Feng Liu, Quanyue Dai, Marcus Kalander, Tongliang Liu, Jianye Hao, and Bo Han.

Keywords: Out-of-distribution Detection, Reliable Machine Learning

Abstract: Outlier exposure (OE) is powerful in out-of-distribution (OOD) detection, enhancing detection capability via model fine-tuning with surrogate OOD data. However, surrogate data typically deviate from test OOD data. Thus, the performance of OE when facing unseen OOD data, can be weaken. To address this issue, we propose a novel OE-based approach that makes the model perform well for unseen OOD situations, even for unseen OOD cases. It leads to a min-max learning scheme---searching to synthesize OOD data that leads to worst judgments and learning from such OOD data for the uniform performance in OOD detection. In our realization, these worst OOD data are synthesized by transforming original surrogate ones, where the associated transform functions are learned implicitly based on our novel insight that model perturbation leads to data transformation. Our methodology offers an efficient way of synthesizing OOD data, which can further benefit the detection model, besides the surrogate OOD data. We conduct extensive experiments under various OOD detection setups, demonstrating the effectiveness of our method against its advanced counterparts.

'''
@inproceedings{
wang2023outofdistribution,
title={Out-of-distribution Detection with Implicit Outlier Transformation},
author={Qizhou Wang and Junjie Ye and Feng Liu and Quanyu Dai and Marcus Kalander and Tongliang Liu and Jianye Hao and Bo Han},
booktitle={International Conference on Learning Representations},
year={2023},
url={https://openreview.net/forum?id=hdghx6wbGuD}
}'''
