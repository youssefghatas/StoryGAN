# StoryGAN: A Sequential Conditional GAN for Story Visualization - Python 3.6 version
Original Repo: 
https://github.com/yitong91/StoryGAN.git

Fork for python 3. Use with caution, not tested. 

## Requirement:
Python 3.6, PyTorch, cv2

## Configure File
/code/cfg/clevr.yml is the configure file for the model. This file contains the setup of the dimension of the features, maximum training epoches and etc.


## Run
To run the code on CLEVR-SV experiment:
```bash
python main_clevr.py
```

## Citation
```bash
@article{li2018storygan,
  title={StoryGAN: A Sequential Conditional GAN for Story Visualization},
  author={Li, Yitong and Gan, Zhe and Shen, Yelong and Liu, Jingjing and Cheng, Yu and Wu, Yuexin and Carin, Lawrence and Carlson, David and Gao, Jianfeng},
  journal={CVPR},
  year={2019}
}
```
