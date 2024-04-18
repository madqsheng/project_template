## 目录

**data**：数据加载

1. dataloader.py：关于dataset的自定义实现
2. train.txt：训练集清单
3. val.txt：验证集清单

**preprocess**：预处理

1. preprocess.py：预处理代码
2. config.py：预处理的配置

**utils**：辅助模块

1. utils.py：辅助函数
2. metrics.py：评估指标

**modules**：模型定义和损失函数

1. model_{name}.py：模型定义
2. loss.py：损失函数定义
3. utils.py：辅助函数

**log**：日志

1. *.log：日志文件

**aug**：数据增强

1. aug.py：数据增强代码
2. config.py：数据增强的配置

**checkpoints**：保存训练好的模型

**model_hub**：预训练模型权重

**configs.py**：配置文件

**train.py**：训练和验证文件

**test.py**：测试文件