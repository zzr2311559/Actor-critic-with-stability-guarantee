# Actor-critic-with-stability-guarantee

## Conda environment
From the general python package sanity perspective, it is a good idea to use conda environments to make sure packages from different projects do not interfere with each other.


To create a conda env with python3, one runs 
```bash
conda create -n test python=3.6
```
To activate the env: 
```
conda activate test
```

# Installation Environment

```bash
git clone https://github.com/hithmh/Actor-critic-with-stability-guarantee
pip install numpy==1.16.3 -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install tensorflow==1.13.1 -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install tensorflow-probability==0.6.0 -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install opencv-python -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install cloudpickle -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install gym -i https://pypi.tuna.tsinghua.edu.cn/simple
pip install matplotlib -i https://pypi.tuna.tsinghua.edu.cn/simple
```

Then you are free to run main.py to train agents. Hyperparameters for training LAC in Cartpole are ready to run by default. If you would like to test other environments and algorithms, please open variant.py and choose corresponding 'env_name' and 'algorithm_name'.

