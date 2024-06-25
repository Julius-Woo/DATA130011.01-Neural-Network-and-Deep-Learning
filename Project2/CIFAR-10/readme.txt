Open folder CIFAR-10 as the working directory.

For hyperparameter tuning, run ResNet18-tuning.ipynb.

For training the model, open main.py and run one of the following commands:

```cmd
python main.py --model ResNet18
python main.py --model ResNet18_filtermul
python main.py --model ResNet18_dropout
python main.py --model ResNet34
```

For visualizing the convolutional filters, run cov_vis.ipynb.