# QuoTe: Quality-oriented Testing for DL Systems
 
This repository contains code for the papers [QuoTe: Quality-oriented Testing for Deep Learning Systems] and [RobOT: Robustness-Oriented Testing for Deep Learning Systems](https://doi.org/10.1109/ICSE43902.2021.00038) (ICSE'21). 


## Prerequisite (Py3 & TF2) 
The code is run successfully using **Python 3.6.10** and **Tensorflow 2.2.0**. 

We recommend using **conda** to install the tensorflow-gpu environment:

```shell
$ conda create -n tf2-gpu tensorflow-gpu==2.2.0
$ conda activate tf2-gpu
```

To run code in the jupyter notebook, you should add the kernel manually: 

```shell
$ pip install ipykernel
$ python -m ipykernel install --name tf2-gpu
```

## Work Flow 
![Snipaste_2022-11-18_17-38-26](https://user-images.githubusercontent.com/95740042/202670553-002de81e-20f5-4a75-a9f6-1b56ce94d6e6.png)


## Files
- `DeepJudge`: Our DeepJudge testing framework.
- `train_models`: train clean models and suspect models.
- `watermarking-whitebox`: a TF2 implementation of [1]. ([Keras version](https://github.com/yu4u/dnn-watermark))
- `watermarking-blackbox`: a TF2 implementation of [2]. 
- `fingerprinting-blackbox`: a TF2 implementation of [3]. 

**Reference:** 


## To Run

See the `README.md` in each directory. 


## Publications 
```
@inproceedings{quote2022,
  author    = {Jialuo Chen and
               Jingyi Wang and
               Tinglan Peng and
               Youcheng Sun and
               Peng Cheng and
               Shouling Ji and
               Xingjun Ma and
               Bo Li and
               Dawn Song},
  title     = {QuoTe: Quality-oriented Testing for Deep Learning Systems},
  booktitle = {},
  year      = {2022},
}
```
```
@inproceedings{robot2011,
  author    = {Jingyi Wang and
               Jialuo Chen and
               Youcheng Sun and
               Xingjun Ma and
               Dongxia Wang and
               Jun Sun and
               Peng Cheng},
  title     = {RobOT: Robustness-Oriented Testing for Deep Learning Systems},
  booktitle = {43rd {IEEE/ACM} International Conference on Software Engineering,
               {ICSE} 2021, Madrid, Spain, 22-30 May 2021},
  year      = {2021},
}
```



