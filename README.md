# Basic_Img_Classification

This is a repository to study the basic image classification.
Especially, we consider CIFAR-10 to deal with image classification task.

# Purpose
Training the model with **CIFAR-10** dataset, and test out the accuracy under various types of model.

# Usage
You can modify the **train.sh** file to adjust the value of each parameter.

```bash
bash train.sh
```
```bash
CUDA_VISIBLE_DEVICES=0 python train.py \
                    --lr 0.1 \
                    --batch_size 512 \
                    --name vgg16
```

# Experiments

| Model |  Accuracy  |  
| :------------ | :------------|
| ResNet18 | |
| ResNet50 | |
| VGG16 | |
| VGG19 | |
| DenseNet121 | |
| InceptionV3 | |

