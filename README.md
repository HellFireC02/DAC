# Deep Adaptive Image Clustering 
IEEE International Conference on Computer Vision 2017 (ICCV 2017 Oral: 2.09%)

Please wait for the core code, we will update it in the next two months.

Keras 1.1.2 + Theano 0.8.2

Jianlong Chang (jianlong.chang@nlpr.ia.ac.cn)

# The core code of DAC*, which considers all samples for training during each iteration. 

# Results visualization
STL-10 results

![](Results_visualization/STL-10.gif)



# Datasets
MNIST, CIFAR10, CIFAR100 can be obtained by Keras (https://keras.io/datasets/).

STL-10 can be founded at http://cs.stanford.edu/~acoates/stl10/.

The descriptions of the ImageNet-10 and ImageNet-Dog datasts are in the "vector-1127/DAC/Datasets description".

# Bibtex
```
@InProceedings{Chang_2017_ICCV,
author = {Chang, Jianlong and Wang, Lingfeng and Meng, Gaofeng and Xiang, Shiming and Pan, Chunhong},
title = {Deep Adaptive Image Clustering},
booktitle = {The IEEE International Conference on Computer Vision (ICCV)},
month = {Oct},
year = {2017}
}
```

hehe this is the update test
please do:
python model_eval.py --config cfgs/Cifar-100/t1.yaml && python model_eval.py --config cfgs/Cifar-100/t2.yaml && python model_eval.py --config cfgs/Cifar-100/t3.yaml
