# COME: Dual Structure-Semantic Learning with Collaborative MoE for Universal Lesion Detection Across Heterogeneous Ultrasound Datasets
We propose the <u>**Co**</u>llaborative <u>**M**</u>ixture of Heterogeneous <u>**E**</u>xperts (COME), a novel framework for lesion detection across multiple heterogeneous US datasets that synergistically integrates dual structural-semantic priors with intra-dataset specific feature disentanglement.


# Datasets
We evaluate the proposed **COME** under three training paradigms for the detection tasks: single dataset, intra-organ consolidation dataset, and inter-organ integration dataset. This includes four breast US datasets (BUS1 [1], BUV [2], BUSBRA [3], BUSC [4] and four thyroid datasets (DDTI [1], TUD [2], TUS [3], TNSCUI [4]), as detailed in the following firgure.  ![picture](https://github.com/UniversalCOME/UniversalCOME/blob/main/img/data.png). 

All datasets exhibit heterogeneous characteristics from different imaging devices or protocols, manifesting as variations in shadow artifacts, speckle noise patterns, intensity distributions, and the scales of regions of interest.
 
[1] BUSI: https://www.kaggle.com/datasets/sabahesaraki/breast-ultrasound-images-dataset/data.  
[2] BUV: Zhi Lin, Junhao Lin, Lei Zhu, Huazhu Fu, Jing Qin, and Liansheng Wang. A new dataset and a baseline model for breast lesion detection in ultrasound videos. In International Conference on Medical Image Computing and Computer-Assisted Intervention, pages 614–623. Springer, 2022. 5.  
[3] BUSBRA: Wilfrido G´omez-Flores, Maria Julia Gregorio-Calas, and Wagner Coelho de Albuquerque Pereira. Bus-bra: a breast ultrasound dataset for assessing computer-aided diagnosis systems. Medical Physics, 51(4):3110–3123, 2024. 1, 5.  
[4] BUSC: Paulo Sergio Rodrigues. Breast ultrasound image. Mendeley Data, 1(10.17632), 2017.  
[5] DDTI: https://www.kaggle.com/datasets/dasmehdixtr/ddti-thyroid-ultrasound-images.  
[6] TUD: https://github.com/NEU-LX/TUD-Datebase.  
[7] TUS: https://www.kaggle.com/datasets/eiraoi/thyroidultrasound.  
[8] TNSCUI: https://tn-scui2020.grand-challenge.org/.  

**We are continuously expanding our intra-organ and inter-organ datasets and will continue to update them in the future...**


# Usage
Device: Experiments are conducted on two NVIDIA RTX 4090 GPUs with 24GB of memory.  
It is highly recommanded to adopt Conda/MiniConda to manage the environment to avoid some compilation errors.

1. Clone the repository

2. Install the dependencies
 * Python 3.10
 * Pytorch 2.0.1
 * Cuda 11.8
 * Other packages

`pip install -r requirements.txt`

# Training 
python **main.py**:

 # Inference
python **eval.sh**

 # Inference
  Results of Lesion Detection Obtained on Inter-Organ Heterogeneous Ultrasound Dataset.
  ![picture](https://github.com/UniversalCOME/UniversalCOME/blob/main/img/result.png)
  
## 🚀 Coming Soon  

We are excited to announce that our project will be **open-sourced soon**! 🎉  

Stay tuned for updates and be ready to explore the code.  

If you are interested, feel free to **star** ⭐ this repository to get notified when we release the code!  



     


