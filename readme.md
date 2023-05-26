# 1.Image Classification 
## Dataset
You can download dataset from [here](https://www.kaggle.com/datasets/obulisainaren/multi-cancer) 

You can get information about this dataset from [here](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/)

## Result
#### DenseNet
![image](https://user-images.githubusercontent.com/100410064/235642378-60c04619-b730-493a-ba7e-803dfacb6c53.png)

#### MobileNet
![image](https://user-images.githubusercontent.com/100410064/235641856-90e0edb8-05c6-40fc-bd62-af23a3b562f1.png)

#### ResNet
![image](https://user-images.githubusercontent.com/100410064/235641606-ad5ff21d-2a90-48aa-a532-c982142baa46.png)

#### ViT
![image](https://user-images.githubusercontent.com/100410064/235641070-464c0a13-f21d-44f2-bf77-364b72afa6cb.png)

#### Inception
![image](https://user-images.githubusercontent.com/100410064/236374400-63312d88-7d70-4144-99ba-f4d7f0dbbfc9.png)

#### ViT+Inception
![image](https://github.com/lthhieu/breast-cancer/assets/100410064/51ece16f-02a4-4394-9dba-5cd521055887)


#### Accuracy - Val_accuracy Chart
![image](https://github.com/lthhieu/breast-cancer/assets/100410064/c2c1fdd7-9283-454e-a840-d8a77c1f4d32)

#### Loss - Val_loss Chart
![image](https://github.com/lthhieu/breast-cancer/assets/100410064/ba981102-8152-46d7-a205-3f7f2a8b53c8)

#### Training time
![image](https://github.com/lthhieu/breast-cancer/assets/100410064/623f2aa0-4543-4d3c-95b9-32ae698e8f8c)

# 2.Image Segmentation 
## Dataset
You can download dataset from [here](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset) 

and [here](https://www.kaggle.com/datasets/lytranhoanghieu/breast-128-malign)

The first link is the main dataset, the second link is the dataset I resized all the images to 128x128 and renamed the malignant to malignant, in addition, I also deleted the images with more than 1 mask.

## Result
#### Unet
![image](https://github.com/lthhieu/breast-cancer/assets/100410064/5ebdbb0c-e0bf-4eba-a8fe-b6873fe7f17c)

#### Attention-Unet
![image](https://github.com/lthhieu/breast-cancer/assets/100410064/6a0f47fb-24d8-4dd6-8fbc-58538c8685be)

#### Densenet121-Unet
![image](https://github.com/lthhieu/node-base/assets/100410064/c9ca7ed6-fcfb-4fd9-bf6a-241515c239e2)


#### Accuracy - Val_accuracy Chart
![image](https://github.com/lthhieu/node-base/assets/100410064/2ddcb098-16f2-4e46-b8a7-682edcc850c6)

#### Loss - Val_loss Chart
![image](https://github.com/lthhieu/node-base/assets/100410064/27e78cbd-adf5-4f9b-8164-9b88e7c52671)


#### Training time
![image](https://github.com/lthhieu/node-base/assets/100410064/e5fe1f4d-3728-4401-8d11-4cd7a7ace666)


