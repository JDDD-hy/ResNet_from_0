# README

### 依赖库列表（Kaggle 环境）：

```python
import numpy as np
import cupy as cp
import os
import math
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.metrics import confusion_matrix
from tqdm.notebook import tqdm
```

Python 3.10：

* `numpy >= 1.23`
* `cupy >= 11.0`
* `matplotlib >= 3.5`
* `seaborn >= 0.11`
* `scikit-learn >= 1.1`
* `tqdm >= 4.64`

---

### 数据集说明：

* 数据集名称：`CIFAR-10`
* 使用的版本：`cifar-10-binary.tar.gz`
* 图像格式：彩色，32×32，10 类

---

### 执行步骤说明：

1. **导入依赖库**
   
2. **加载 CIFAR-10 数据集**
   解压 `cifar-10-binary.tar.gz`，按照如下结构放置。
```
/kaggle/  
├── input/  
│   └── cifar-10-batches-bin/  
│       ├── data_batch_1.bin  
│       ├── data_batch_2.bin  
│       ├── data_batch_3.bin  
│       ├── data_batch_4.bin  
│       ├── data_batch_5.bin  
│       └── test_batch.bin  
├── working/  
│   └──我的作业代码文件
```

3. **运行代码**
    时长大约2-3小时
    

