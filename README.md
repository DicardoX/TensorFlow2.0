# Tensorflow2.0

## `conda`指令的使用（每次使用都要操作一次）

- 使用`export PATH=~/anaconda3/bin:$PATH`指令更改环境变量.

---------

## 命令行安装TensorFlow2.0

- 创建独立环境并激活：
 
```
  conda create --name tensorflow2.0 python==3.8.5       // 创建
  source activate tensorflow2.0                         // 激活
```
  &emsp;运行结果：
   
```
  dicardo@MacBook-Pro ~ % source activate tensorflow2.0
  (tensorflow2.0) dicardo@MacBook-Pro ~ %                 // 已经进入tensorflow2.0环境
```

- 安装相关软件包：

```
  pip3 install numpy matplotlib Pillow scikit-learn pandas -i https://pypi.tuna.tsinghua.edu.cn/simple
```

- 安装TensorFlow2.3.0

```
   pip3 install tensorflow==2.3.0 -i https://pypi.tuna.tsinghua.edu.cn/simple
```

- 测试TensorFlow2.0是否成功

```
  (tensorflow2.0) dicardo@MacBook-Pro ~ % python3
```

&emsp; 在Python交互模式输入：

```
  import tensorflow as tf
```

&emsp; 没有报错即安装成功。

------------

## 使用conda管理环境

```
  // 创建环境
  conda create --name tensorflow2.0 python==3.8.5       
  // 激活环境
  source activate tensorflow2.0                         
  // 退出环境
  (tensorflow2.0) dicardo@MacBook-Pro ~ % conda deactivate
  // 删除环境
  conda remove –name <env_name> –all
  // 环境列表
  conda env list
```

--------------

## TensorFlow的使用

&emsp; 每次需要在命令行进入(tensorflow2.0)环境之后，使用：

```
  python fileName.py
```

&emsp; 来调用.py文件，在文件内可以调用tensorflow库。




