# [Image-Procccessing](https://github.com/Amir-h055/Image-Procccessing)
</br>

### Table of Contents
1. [Contributors](#Contributor)
2. [Datsset](#Dataset)
3. [Description](#Description)

</br>

## Contributor
@Amir-h055 AmirHossein </br>
@@isratnoor Israt Noor Kazi </br>

## Dataset
[Link](https://www.kaggle.com/datasets/prashant268/chest-xray-covid19-pneumonia)

This study has used X-ray imagery from a dataset obtained from kaggle. The dataset contains 5144 chest X-ray images for training and 1288 chest X-ray images for test.It is divided into three categories. The following categories for training include:

460 X-ray images of people with COVID-19

1266 X-ray images of healthy people

3418 X-ray images of people with

## Description

Since our dataset was not Balanced , we tried to tackle that issue by augmenting images with less number ( Covid, and normal). Since Cross validation wouldn't necessarily be helpful for us we divide our given dataset(train) into a new train and validation set then only Augment the train dataset. After that we developed and observed different training and built an architecture that can learn the model and build afew models and some with pretrained  models. Most of the final results are pretty accurate at detecting Covid as it is the main purpose of the training . Also we considered different performance matrix to tackle our imbalance data and enhance our detecting model ie: Categorical accuracy, f1,recall, weighted avg.  Out of all of the Models, EfficientNetB0 seems to be slightly better than others, we could still work on our own models or enhance them but we already got good result
