# PointNetPartAffordance

This project is based on the following papers:
  * [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation][1]
  * [Towards affordance detection for robot manipulation using affordance for parts and parts for affordance][2]
  
 The Part Affordance Dataset we used:
  * [RGB-D Part Affordance Dataset][3]
  
Reused Code:
  * [PointNet.pytorch][4]
  * [Open3D-PointNet][5]
  
 
 ## Setup
 Install Open3d
 `pip install open3d-python`
 
 Install Pytorch
 `https://pytorch.org/`
 
 [Download Dataset][3]
 
 Use the jupyter notebooks for:
  * Dataset Cleaning - clean_dataset.ipynb
  * Segmentation Training - training.ipynb
  * Segmentation Testing - segmentation_testing.ipynb
  
  ## Example Results
  
  ![Ground Truth Segmentation](/img/scissor_gt.png =250x)

[1]:https://arxiv.org/abs/1612.00593
[2]:https://link.springer.com/article/10.1007/s10514-018-9787-5
[3]:http://users.umiacs.umd.edu/~amyers/part-affordance-dataset/
[4]:https://github.com/fxia22/pointnet.pytorch
[5]:https://github.com/intel-isl/Open3D-PointNet


