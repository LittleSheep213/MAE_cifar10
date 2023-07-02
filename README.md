# MAE_cifar10

### Installation
`pip install -r requirements.txt`

### Run
```bash
# pretrained with mae
python mae_pretrain.py

# train classifier from scratch
python train_classifier.py

# train classifier from pretrained model
python train_classifier.py --pretrained_model_path vit-t-mae.pt --output_model_path vit-t-classifier-from_pretrained.pt
```

See logs by `tensorboard --logdir logs`.


