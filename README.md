# Chinese super-resolution text recognition

This repository is the coding about our paper "Chinese Low-resolution Image Text Recognition by Introducing Super-Resolution Network".

Currently, we only push the key module of our model in this repository,our paper is supported by DONGPU Software Co.,Ltd in China,

due to commercial agreement，we will not provide the whole scripts at the present before our paper have been considered for acceptance. 

But, we have provided the key module part in path "/models/model_builder.py" including our model framework, which can give the readers inspirations and provide ideas.


## What we did not provide

we did not provide the data processing script in this repository, considering the commercial agreement and we will provide this part in future.

If readers have any questions, please email us (hengherui@stu.shmtu.edu.cn / lipeiji@yundaex.com / shaopengshang@126.com ) at any time. We are welcome to have further 

discussion.


## training enviroment

Tesla V100 32G memory, 8 cards.

install required package "pip install -r requirments" 





## Data preparation

We give an example to construct your own datasets. Details please refer to `tools/create_svtp_lmdb.py`.

We provide datasets for [training](https://pan.baidu.com/s/1BMYb93u4gW_3GJdjBWSCSw&shfl=sharepset) (password: wi05) and [testing](https://drive.google.com/open?id=1U4mGLlsm9Ade1-gQOyd6He5R0yiaafYJ).
