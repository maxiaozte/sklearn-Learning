# sklearn-Learning
sklearn学习

## train_test_split
from sklearn.model_selection import train_test_split
train_test_split函数有一个参数stratify
stratify: array-like or None (default=None)
If not None, data is split in a stratified fashion, using this as the class labels.
设置stratify参数= class labels，可以保证train_set、test_set类别比例与整个样本集一致
