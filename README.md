# CBT

**A new Cross Band Transformer (CBT) architecture for pansharpening of satellite imagery**

TODO citation


# Performance on benchmark datasets


<img src="https://github.com/nickdndndn/CBT/blob/main/Images/comparison.png?raw=true" alt="alt text" width=500>

![alt text](https://github.com/nickdndndn/CBT/blob/main/Images/visualization.png?raw=true)



# Performance on real world datasets

# Datasets

The GaoFen-2 and WorldView-3 dataset download links can be found [here](https://github.com/liangjiandeng/PanCollection)

| Method        | GaoFen-2           | WorldView-3  |
| ------------- |:-------------:| -----:|
| PNN     | PSNR | SSIM | PSNR | SSIM|
| PanNet     | centered      |   $12 |
| MSDCNN | are neat      |    $1 |
| GPPNN | are neat      |    $1 |
| CBT | are neat      |    $1 |
| ------------------------------- |
| PanFormer | are neat      |    $1 |
| ArbRPN | are neat      |    $1 |
| CBTLarge | are neat      |    $1 |


Method GaoFen-2 WorldView-3
PSNR SSIM PSNR SSIM
PNN 36.3094 0.9350 31.2246 0.9042
PanNet 37.9091 0.9533 33.1460 0.9484
MSDCNN 38.1485 0.9563 33.5880 0.9552
GPPNN 36.1538 0.9371 34.6712 0.9615
CBT 42.5083 0.9770 36.6498 0.9731
PanFormer 40.1886 0.9654 35.4781 0.9427
ArbRPN 43.9760 0.9827 37.5401 0.9775
CBTLarge 44.8258 0.9853 37.7194 0.9783

Sample data (test sets) can be downloaded from [here](https://drive.google.com/file/d/1ptOImqdEM94P6Ev0Un99EjDS4CohKHO4/view?usp=sharing)

# TODO add Sev2Mod dataset link

# Benchmark methods used in the study

 Implementation of benchmark methods with pretrained weights on GaoFen-2 and WorldView3 datasets.
 
- [ArbRPN](https://github.com/nickdndndn/ArbRPN)
- [PanFormer](https://github.com/nickdndndn/PanFormer)
- [GPPNN](https://github.com/nickdndndn/GPPNN)
- [MSDCNN](https://github.com/nickdndndn/MSDCNN)
- [PanNet](https://github.com/nickdndndn/PanNet)
- [PNN](https://github.com/nickdndndn/PNN)

# Set Up

# Train

# Validate

`
python3 evaluate.py -c CBT_base_server_T_GF2.yaml
`

# Inference
