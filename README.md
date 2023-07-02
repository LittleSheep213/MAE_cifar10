# MAE_cifar10

### 安装
`pip install -r requirements.txt`

### 训练
# pretrained with mae
python mae_pretrain.py

# train classifier from scratch
python train_classifier.py

# train classifier from pretrained model
python train_classifier.py --pretrained_model_path vit-t-mae.pt --output_model_path vit-t-classifier-from_pretrained.pt
```

See logs by `tensorboard --logdir logs`.


### 模型参数
链接：https://pan.baidu.com/s/1ht-RGNfDS-o7hj69LgUrFg 
提取码：gy36 
在目录mae文件夹下有三个权重文件



