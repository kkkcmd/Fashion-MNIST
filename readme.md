### 代码运行方式

直接运行ipynb文件即可，如若要对参数进行调整，在下面位置设置参数调整范围，分别对应学习率、隐藏层大小、正则化强度。

```python
def hyperparameter_search(X_train, y_train, X_val, y_val):

​    learning_rates = [0.1, 0.2]

​    hidden_sizes = [(128,128),(256,256)]

​    regularization_strengths = [0.001, 0.005, 0.01]
```



另外两个单元分别为训练过程可视化和模型权重可视化