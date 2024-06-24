## 使用说明
本项目基于ResNet50模型进行Fine-Tuning，适用于在**Colab**上训练模型的情景。当然，如果你希望在自己的设备上训练模型，也可以注释掉和Colab相关的代码。
使用方法：
```
git clone https://github.com/dp0qb/MineralIdentification.git
cd ./MineralIdentification
pip install -r ./requirements.txt
```
安装好依赖后，就可以运行ore_rec.ipynb中的代码进行训练了。
minerals目录下是以各个矿物的英文名称为名的目录，包含对应的矿物图片。如果有更多数据，按照同样的规则加入即可。
模型参数保存在ore_weights目录下，训练出满意的结果后可以提取出来用于其它用途（比如放在服务器上提供识别服务等...），此处不加赘述。