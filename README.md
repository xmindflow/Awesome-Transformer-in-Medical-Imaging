# Medical Image Analysis with Transformers: A Review

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

:fire::fire:This is a collection of awesome articles about transformer models in the medical imaging:fire::fire:

:loudspeaker: Our survey paper published on arXiv: [Medical Image Analysis with Transformers: A Review]() :heart:

#### Citation

```

```

## Contents

- [Survey Papers in Vision](#survey-papers-in-vision)

- [Papers](#papers)
  
  - [Image Classification](#Image-Classification)
  - [Image Segmentation](#Image-Segmentation)
  - [Image Reconstruction](#Image-Reconstruction)
  - [Image Synthesizing](#Image-Synthesizing)
  - [Object Detection](#Image-Detection)
  - [Image Denoising](#Image-Denoising)
  - [Image Registration](#Image-Registration)
  - [Report Generation](#Report-Generation)

## Survey Papers in Vision

## Papers

### Image-Classification

**Training data-efficient image transformers & distillation through attention.** [15th Jan., 2021] [ICML, 2021]<br>
*Huisi Wu, Shihuai Chen, Guilian Chen, Wei Wang, Baiying Lei, Zhenkun Wen.*<br>
 [[PDF](https://arxiv.org/pdf/2012.12877)] [[Github](https://github.com/facebookresearch/deit)]

**CrossViT: Cross-Attention Multi-Scale Vision Transformer for Image Classification.** [22nd Aug., 2021] [ICCV, 2021]<br>
*Chun-Fu Chen, Quanfu Fan, Rameswar Panda.*<br>
 [[PDF](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_CrossViT_Cross-Attention_Multi-Scale_Vision_Transformer_for_Image_Classification_ICCV_2021_paper.pdf)] [[Github](https://github.com/IBM/CrossViT)]

---

### Image-Segmentation

**Swin-Unet: Unet-like Pure Transformer for Medical Image Segmentation.**[12th May, 2021]  <br>
*Hu Cao, Yueyue Wang, Joy Chen, Dongsheng Jiang, Xiaopeng Zhang, Qi Tian, Manning Wang.*  <br>
[[PDF](https://arxiv.org/abs/2105.05537)] [[Github](https://github.com/HuCaoFighting/Swin-Unet)]

**nnFormer: Interleaved Transformer for Volumetric Segmentation.**[4th Feb., 2022]<br>



*Hong-Yu Zhou, Jiansen Guo, Yinghao Zhang, Lequan Yu, Liansheng Wang, Yizhou Yu*<br>



[[PDF]](https://arxiv.org/abs/2109.03201) [[Github]](https://github.com/282857341/nnFormer)

**MISSFormer: An Effective Medical Image Segmentation Transformer.**[19th Dec., 2021]<br>



*Xiaohong Huang, Zhifang Deng, Dandan Li, Xueguang Yuan*<br>



[[PDF]](https://arxiv.org/abs/2109.07162) [[Github]](https://github.com/ZhifangDeng/MISSFormer)

TransDeepLab: Convolution-Free Transformer-based DeepLab v3+ for Medical Image Segmentation.[1st Aug., 2022]<br>



*Reza Azad, Moein Heidari, Moein Shariatnia, Ehsan Khodapanah Aghdam, Sanaz Karimijafarbigloo, Ehsan Adeli, Dorit Merhof*<br>



[[PDF]](https://arxiv.org/abs/2208.00713) [[Github]](https://github.com/rezazad68/transdeeplab)

**TransUNet: Transformers Make Strong Encoders for Medical Image Segmentation.** [8th Feb., 2021]<br>


*Jieneng Chen, Yongyi Lu, Qihang Yu, Xiangde Luo, Ehsan Adeli, Yan Wang, Le Lu, Alan L. Yuille, Yuyin Zhou.*<br>
 [[PDF](https://arxiv.org/abs/2102.04306)] [[Github](https://github.com/Beckschen/TransUNet)]

**TransBTS: Multimodal Brain Tumor Segmentation Using Transformer.**[7th Mar, 2021] [MICCAI, 2021]<br>
*Jiangyun Li, Wenxuan Wang, Chen Chen, Tianxiang Zhang, Sen Zha, Hong Yu, Jing Wang.*<br>
 [[PDF](https://arxiv.org/abs/2103.04430)] [[Github](https://github.com/Wenxuan-1119/TransBTS)]

**TransFuse: Fusing Transformers and CNNs for Medical Image Segmentation.**[16th Feb., 2021]<br>
*Yundong Zhang, Huiye Liu, Qiang Hu.*<br>
 [[PDF](https://arxiv.org/abs/2102.08005)] [[Github]()]

**Medical Transformer: Gated Axial-Attention for Medical Image Segmentation.**[21th Feb., 2021] [MICCAI, 2021]<br>
*Jeya Maria Jose Valanarasu, Poojan Oza, Ilker Hacihaliloglu, Vishal M. Patel.*<br>
 [[PDF](https://arxiv.org/abs/2102.10662)] [[Github](https://github.com/jeya-maria-jose/Medical-Transformer)]

**UNETR: Transformers for 3D Medical Image Segmentation.**[18th Mar., 2021]<br>
*Ali Hatamizadeh, Yucheng Tang, Vishwesh Nath, Dong Yang, Andriy Myronenko, Bennett Landman, Holger Roth, Daguang Xu.*<br>
 [[PDF](https://arxiv.org/abs/2103.10504)] [[Github](https://github.com/Project-MONAI/research-contributions/tree/main/UNETR/BTCV)]

**Swin UNETR: Swin Transformers for Semantic Segmentation of Brain Tumors in MRI Images.**[4th Jan., 2022]  <br>
*Ali Hatamizadeh, Vishwesh Nath, Yucheng Tang, Dong Yang, Holger Roth, Daguang Xu.*  <br>
[[PDF](https://arxiv.org/abs/2201.01266)] [[Github](https://github.com/Project-MONAI/research-contributions/tree/main/SwinUNETR)]



**CoTr: Efficiently Bridging CNN and Transformer for 3D Medical Image Segmentation.**[4th Mar., 2021] [MICCAI, 2021]  <br>
*Yutong Xie, Jianpeng Zhang, Chunhua Shen, Yong Xia.* <br>
[[PDF](https://arxiv.org/abs/2103.03024)] [[Github](https://github.com/YtongXie/CoTr)]

**HiFormer: Hierarchical Multi-scale Representations Using Transformers for
Medical Image Segmentation.**[18th Jul., 2022]<br>



*Moein Heidari, Amirhossein Kazerouni, Milad Soltany, Reza Azad, Ehsan Khodapanah, Aghdam Julien Cohen-Adad, Dorit Merhof.*<br>



[[PDF]](https://arxiv.org/abs/2207.08518) [[Github]](https://github.com/amirhossein-kz/HiFormer)

**Medical Image Segmentation Using Squeeze-and-Expansion Transformers.**[20th May, 2021] [IJCAI, 2021 ]<br>
*Shaohua Li, Xiuchao Sui, Xiangde Luo, Xinxing Xu, Yong Liu, Rick Goh.*<br>
 [[PDF](https://arxiv.org/abs/2105.09511)] [[Github](https://github.com/askerlee/segtran)]

**T-AutoML: Automated Machine Learning for Lesion Segmentation using Transformers in 3D Medical Imaging.**[15th Nov., 2021] [ICCV, 2021]<br>
*Dong Yang, Andriy Myronenko, Xiaosong Wang, Ziyue Xu, Holger R. Roth, Daguang Xu.*<br>
 [[PDF](https://arxiv.org/abs/2111.07535)] [[Github]()]

**Semi-Supervised Medical Image Segmentation via Cross Teaching between CNN and Transformer.**[9th Dec., 2021]<br>
*Xiangde Luo, Minhao Hu, Tao Song, Guotai Wang, Shaoting Zhang.*<br>
 [[PDF](https://arxiv.org/abs/2112.04894)] [[Github](https://github.com/HiLab-git/SSL4MIS)]

**Self Pre-training with Masked Autoencoders for Medical Image Analysis.**[10th Mar., 2022]<br>
*Lei Zhou, Huidong Liu, Joseph Bae, Junjun He, Dimitris Samaras, Prateek Prasanna.*<br>
 [[PDF](https://arxiv.org/abs/2203.05573)] [[Github]()]



### Image-Reconstruction

---

### Image-Synthesizing


**One Model to Synthesize Them All: Multi-contrast Multi-scale Transformer for Missing Data Imputation.**[28th Apr., 2022]<br>
*Jiang Liu, Srivathsa Pasumarthi, Ben Duffy, Enhao Gong, Greg Zaharchuk, Keshav Datta.*<br>
 [[PDF](https://arxiv.org/abs/2204.13738)] 
 
---

### Object-Detection

---

### Image-Denoising

**TransCT: Dual-path Transformer for Low Dose Computed Tomography.** [5th Jul., 2021 ] [MICCAI, 2021]<br>
*Zhicheng Zhang, Lequan Yu, Xiaokun Liang, Wei Zhao, Lei Xing.*<br>
 [[PDF](https://arxiv.org/pdf/2103.00634)] [[Github](https://github.com/zzc623/TransCT)]

**TED-net: Convolution-free T2T Vision Transformer-based Encoder-decoder Dilation network for Low-dose CT Denoising.** [8th jun., 2021] [MICCAI, 2021]<br>
*Dayang Wang, Zhan Wu, Hengyong Yu.*<br>
[[PDF](https://arxiv.org/pdf/2106.04650)] [[Github](https://github.com/wdayang/CTformer)]

**Eformer: Edge Enhancement based Transformer for Medical Image Denoising.** [9th Nov., 2021] [ICCV, 2021]<br>
*Achleshwar Luthra, Harsh Sulakhe, Tanish Mittal, Abhishek Iyer, Santosh Yadav.*<br>
[[PDF](https://arxiv.org/pdf/2109.08044)] ~~[[Github]()]~~

**Spatial adaptive and transformer fusion network (STFNet) for low‐count PET blind denoising with MRI.** [8th Nov., 2021] [Medical Physics]<br>
*Lipei Zhang, Zizheng Xiao, Chao Zhou, Jianmin Yuan, Qiang He, Yongfeng Yang, Xin Liu, Dong Liang, Hairong Zheng, Wei Fan, Xu Zhang, Zhanli Hu.*<br>
 [[PDF](https://aapm.onlinelibrary.wiley.com/doi/epdf/10.1002/mp.15368)] ~~[[Github]()]~~

**CTformer: Convolution-free Token2Token Dilated Vision Transformer for Low-dose CT Denoising.** [28th Feb., 2022]<br>
*Dayang Wang, Fenglei Fan, Zhan Wu, Rui Liu, Fei Wang, Hengyong Yu.*<br>
[[PDF](https://arxiv.org/pdf/2202.13517)] [[Github](https://github.com/wdayang/CTformer)]

**Low-Dose CT Denoising via Sinogram Inner-Structure Transformer.** [18th Apr., 2022]<br>
*Liutao Yang, Zhongnian Li, Rongjun Ge, Junyong Zhao, Haipeng Si, Daoqiang Zhang.*<br>
[[PDF](https://arxiv.org/pdf/2204.03163)] ~~[[Github]()]~~

**Adversarial Distortion Learning (ADL) for Medical Image Denoising.** [29th Apr., 2022]<br>
*Morteza Ghahremani, Mohammad Khateri, Alejandra Sierra, Jussi Tohka.*<br>
[[PDF](https://arxiv.org/pdf/2204.14100)] [[Github](https://github.com/mogvision/adl)]

---

### Image-Registration

**ViT-V-Net: Vision Transformer for Unsupervised Volumetric Medical Image Registration.** [13th Apr., 2021]<br>
*Junyu Chen, Yufan He, Eric C. Frey, Ye Li, Yong Du.*<br>
[[PDF](https://arxiv.org/abs/2104.06468)] [[Github](https://github.com/junyuchen245/ViT-V-Net_for_3D_Image_Registration_Pytorch)]

**TransMorph: Transformer for unsupervised medical image registration.** [19th Nov., 2021]<br>
*Junyu Chen, Eric C. Frey, Yufan He, William P. Segars, Ye Li, Yong Du.*<br>
[[PDF](https://arxiv.org/abs/2111.10480)] [[Github](https://github.com/junyuchen245/TransMorph_Transformer_for_Medical_Image_Registration)]

**Affine Medical Image Registration with Coarse-to-Fine Vision Transformer.** [29th Mar., 2022] [CVPR, 2021]<br>
*Tony C. W. Mok, Albert C. S. Chung.*<br>
[[PDF](https://arxiv.org/abs/2203.15216)] [[Github](https://github.com/cwmok/C2FViT)]

**Learning dual transformer network for diffeomorphic registration.** [21th Sep., 2021] [MICCAI, 2021]<br>
*Yungeng Zhang, Yuru Pei & Hongbin Zha.*<br>
[[PDF](https://link.springer.com/chapter/10.1007/978-3-030-87202-1_13)]

**XMorpher: Full Transformer for Deformable Medical Image Registration via Cross Attention.** [15th Jun., 2022] [MICCAI, 2021]<br>
*Jiacheng Shi, Yuting He, Youyong Kong, Jean-Louis Coatrieux, Huazhong Shu, Guanyu Yang, Shuo Li.*<br>
[[PDF](https://arxiv.org/abs/2206.07349)] [[Github](https://github.com/solemoon/xmorpher)]

**SVoRT: Iterative Transformer for Slice-to-Volume Registration in Fetal Brain MRI.** [22th Jun., 2022] [MICCAI, 2022]<br>
*Junshen Xu, Daniel Moyer, P. Ellen Grant, Polina Golland, Juan Eugenio Iglesias, Elfar Adalsteinsson.*<br>
[[PDF](https://arxiv.org/abs/2206.10802?context=eess)] [[Github](https://github.com/daviddmc/svort)]

---

### Report-Generation

**Knowledge-driven Encode, Retrieve, Paraphrase for Medical Image Report Generation.** [25th Mar., 2019] [AAAI, 2019]<br>
*Christy Y. Li, Xiaodan Liang, Zhiting Hu, Eric P. Xing.*<br>
[[PDF](https://arxiv.org/abs/1903.10122)] 

**Reinforced Transformer for Medical Image Captioning.** [10th Oct., 2019]<br>
*Yuxuan Xiong, Bo Du, Pingkun Yan.*<br>
[[PDF](https://doi.org/10.1007/978-3-030-32692-0_77)] ~~[[Github]()]~~

**Surgical Instruction Generation with Transformers.** [16th Jul., 2021] [MICCAI, 2021]<br>
*Jinglu Zhang, Yinyu Nie, Jian Chang, Jian Jun Zhang.*<br>
[[PDF](https://arxiv.org/abs/2107.06964)]  ~~[[Github]()]~~

**Learning to Generate Clinically Coherent Chest X-Ray Reports.** [16th Jul., 2021] [emnlp, 2020]<br>
*Justin Lovelace, Bobak Mortazavi.*<br>
[[PDF](https://aclanthology.org/2020.findings-emnlp.110/)] [[Github](https://github.com/justinlovelace/coherent-xray-report-generation)]

**Automated Generation of Accurate \& Fluent Medical X-ray Reports.** [27th Jul., 2021] [emnlp, 2021]<br>
*Hoang T.N. Nguyen, Dong Nie, Taivanbat Badamdorj, Yujie Liu, Yingying Zhu, Jason Truong, Li Cheng.*<br>
[[PDF](https://arxiv.org/abs/2108.12126)] [[Github](https://github.com/ginobilinie/xray_report_generation)]

**Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation.** [13th Jun., 2021] [CVPR, 2021]<br>
*Fenglin Liu, Xian Wu, Shen Ge, Wei Fan, Yuexian Zou.*<br>
[[PDF](https://arxiv.org/abs/2106.06963)]

**Medical-vlbert: Medical visual language bert for covid-19 ct report generation with alternate learning.** [18th Aug., 2021] [IEEE Transactions on Neural Networks and Learning Systems, 2021]<br>
*Guangyi Liu, Yinghong Liao, Fuyu Wang, Bin Zhang, Lu Zhang, Xiaodan Liang, Xiang Wan, Shaolin Li, Zhen Li, Shuixing Zhang, Shuguang Cui.*<br>
[[PDF](https://arxiv.org/abs/2108.05067)] 

**Progressive Transformer-Based Generation of Radiology Reports.** [31th Aug., 2021]<br>
*Farhad Nooralahzadeh, Nicolas Perez Gonzalez, Thomas Frauenfelder, Koji Fujimoto, Michael Krauthammer.*<br>
[[PDF](https://arxiv.org/abs/2102.09777)] [[Github](https://github.com/uzh-dqbm-cmi/argon)]

**Trust It or Not: Confidence-Guided Automatic Radiology Report Generation.** [3th Feb., 2022]<br>
*Yixin Wang, Zihao Lin, Zhe Xu, Haoyu Dong, Jiang Tian, Jie Luo, Zhongchao Shi, Yang Zhang, Jianping Fan, Zhiqiang He.*<br>
[[PDF](https://arxiv.org/abs/2106.10887)]

**AlignTransformer: Hierarchical Alignment of Visual Regions and Disease Tags for Medical Report Generation.** [18th Mar., 2022] [MICCAI, 2021]<br>
*Di You, Fenglin Liu, Shen Ge, Xiaoxia Xie, Jing Zhang, Xian Wu.*<br>
[[PDF](https://arxiv.org/abs/2203.10095)] 

**Generating Radiology Reports via Memory-driven Transformer.** [28th Apr., 2022] [EMNLP, 2020]<br>
*Zhihong Chen, Yan Song, Tsung-Hui Chang, Xiang Wan.*<br>
[[PDF](https://arxiv.org/abs/2010.16056)] [[Github](https://github.com/cuhksz-nlp/R2Gen)]

**Cross-modal Memory Networks for Radiology Report Generation.** [28th Apr., 2022] [ACL-IJCNLP, 2021]<br>
*Zhihong Chen, Yaling Shen, Yan Song, Xiang Wan.*<br>
[[PDF](https://arxiv.org/abs/2204.13258)] [[Github](https://github.com/zhjohnchan/R2GenCMN)]

---
