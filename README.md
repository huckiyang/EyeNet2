# EyeNet2, U-Net Segementation on Drive, ACCV 2018
If you think this repo helps your research, please consider ref this paper (ACCV Workshop 2018, oral.) Thanks!
A U-Net Segmentation is trained on the classical ![Drive](https://drive.grand-challenge.org/) dataset. (was released in 2017)

Georgia Tech, KAUST, Kyoto U

[Yang, C-H. Huck, et al. "Auto-classification of retinal diseases in the limit of sparse data using a two-streams machine learning model." Asian Conference on Computer Vision. Springer, Cham, 2018.](https://arxiv.org/pdf/1808.05754.pdf)

```
@inproceedings{yang2018auto,
  title={Auto-classification of retinal diseases in the limit of sparse data using a two-streams machine learning model},
  author={Yang, C-H Huck and Liu, Fangyu and Huang, Jia-Hong and Tian, Meng and Lin, MD I-Hung and Liu, Yi Chieh and Morikawa, Hiromasa and Yang, Hao-Hsiang and Tegn{\`e}r, Jesper},
  booktitle={Asian Conference on Computer Vision},
  pages={323--338},
  year={2018},
  organization={Springer}
}
```
Supplymentary 2019

# Run

```shell
python run_training.py
```

## Demo: U-Net Segmentation of Retinal Vessel

<img src="https://github.com/huckiyang/huckiyang.github.io/blob/master/assets/img/Unet.png" width="400">

(a) Test Image (b) Ground Truth (c) Automatic Segementation after U-Net Image Model 


## PR-Curve of U-Net for Retina 

<img src="https://github.com/huckiyang/EyeNet2/blob/master/src/Precision_recall.png" width="400">

## ROC of U-Net for Retina 

<img src="https://github.com/huckiyang/EyeNet2/blob/master/src/ROC.png" width="400">
