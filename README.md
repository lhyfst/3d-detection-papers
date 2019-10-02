# 3d detection papers

> Author: Li Heyuan (李贺元)<br>
> Email: lhyfst@gmail.com<br>
> The papers in this list are about Autonomous Vehicles 3d detection & semantic segmentation<br>
> especially those using point clouds and in deep learning methods.<br>
> All rights reserved


If you have any suggestion or want to recommend new papers, please feel free to let me know.<br>
I have read most of the papers here, and am very happy to discuss with you if you have any issues on these papers.<br>
I will keep updating this project continuously.<br>

---

I will improve this project in a few days.<br>

todo list:
1. links  -- done
2. recommended papers  -- done. The ones that I particularly liked are marked with :star:. 
3. authors -- done
4. models  -- remove this item
5. relevant code  -- done
6. rank by year  -- done
7. active researchers  -- done
8. write a brief review for each mainstream method
9. try to write some reviews for the recommended papers, if I have time.


## Mainstream Method Series
- Voxel
- Multi-view
- Pointnet
- Other

## Voxel
- [Sliding shapes for 3d object detection in depth images](http://slidingshapes.cs.princeton.edu/paper.pdf), 
Shuran Song, Jianxiong Xiao, 
[code](http://slidingshapes.cs.princeton.edu/), 
[website](http://slidingshapes.cs.princeton.edu/), 
ECCV, 2014
- [Voxnet: A 3d convolutional neural network for real-time object recognition](https://www.ri.cmu.edu/pub_files/2015/9/voxnet_maturana_scherer_iros15.pdf), 
Daniel Maturana and Sebastian Scherer,
[code](https://github.com/dimatura/voxnet), 
[website](http://dimatura.net/research/voxnet/), 
IROS, 2015 
- [Deep sliding shapes for amodal 3d object detection in rgb-d images](http://dss.cs.princeton.edu/paper.pdf), 
Shuran Song, Jianxiong Xiao, 
[code](https://github.com/shurans/DeepSlidingShape), 
[website](http://dss.cs.princeton.edu/), 
CVPR, 2016
- [Octnet: Learning deep 3d representations at high resolutions](https://arxiv.org/pdf/1611.05009.pdf), 
Gernot Riegler, Ali Osman Ulusoy, Andreas Geiger, 
[code](https://github.com/griegler/octnet), 
CVPR, 2017  :star:
- [3d fully convolutional network for vehicle detection in point cloud](https://arxiv.org/pdf/1611.08069.pdf), 
Gernot Riegler, Ali Osman Ulusoy, Andreas Geiger, 
[unofficial code](https://github.com/yukitsuji/3D_CNN_tensorflow), 
IROS, 2017
- [Voting for voting in online point cloud object detection](http://www.robots.ox.ac.uk/~mobile/Papers/2015RSS_wang.pdf), 
Dominic Zeng Wang, Ingmar Posner,
Robotics: Science and System, 2015
- [Vote3deep: Fast object detection in 3d point clouds using efficient convolutional neural networks](https://arxiv.org/pdf/1609.06666),
Martin Engelcke, Dushyant Rao, Dominic Zeng Wang, Chi Hay Tong, Ingmar Posner, 
ICRA, 2017


## Multi-view
- [Pedestrian detection combining RGB and dense LIDAR data](https://ieeexplore.ieee.org/document/6943141), 
Cristiano Premebida, João Carreira, Jorge Batista, Urbano Nunes, 
IROS, 2014
- [3d-assisted feature synthesis for novel views of an object](http://openaccess.thecvf.com/content_iccv_2015/papers/Su_3D-Assisted_Feature_Synthesis_ICCV_2015_paper.pdf), 
Hao Su, Fan Wang, Eric Yi, Leonidas Guibas, 
ICCV, 2015
- [Multiview random forest of local experts combining rgb and lidar data for pedestrian detection](https://ieeexplore.ieee.org/document/7225711), 
A. González, G. Villalonga, J. Xu, D. Vázquez, J. Amores, and A. López., 
IEEE Intelligent Vehicles Symposium, 2015
- [Multiview convolutional neural networks for 3d shape recognition](http://vis-www.cs.umass.edu/mvcnn/docs/su15mvcnn.pdf), 
Hang Su Subhransu Maji Evangelos Kalogerakis Erik Learned-Miller, 
[code](https://github.com/jongchyisu/mvcnn_pytorch)
ICCV, 2015
- [Vehicle detection from 3d lidar using fully convolutional network](https://arxiv.org/pdf/1608.07916.pdf), 
Bo Li, Tianlei Zhang, Tian Xia, 
Robotics: Science and System, 2016
- [Volumetric and multi-view cnns for object classification on 3d data](http://openaccess.thecvf.com/content_cvpr_2016/papers/Qi_Volumetric_and_Multi-View_CVPR_2016_paper.pdf), 
Charles R. Qi, Hao Su, Matthias Niessner, Angela Dai, Mengyuan Yan, Leonidas J. Guibas, 
CVPR, 2016
- [Fusionnet: 3d object classification using multiple data representations](https://arxiv.org/pdf/1607.05695.pdf), 
Vishakh Hegde, Reza Zadeh, 
CoRR, 2016
- [Multi-view 3d object detection network for autonomous driving](https://arxiv.org/pdf/1611.07759.pdf), 
Xiaozhi Chen, Huimin Ma, Ji Wan, Bo Li, Tian Xia, 
[code](https://github.com/bostondiditeam/MV3D), 
CVPR, 2017  :star:
- [Joint 3d proposal generation and object detection from view aggregation](https://arxiv.org/pdf/1712.02294.pdf), 
Jason Ku, Melissa Mozifian, Jungwook Lee, Ali Harakeh, Steven L. Waslander, 
[code](https://github.com/kujason/avod), 
IROS, 2018
- [Pixor: Real-time 3d object detection from point clouds](https://arxiv.org/pdf/1902.06326), 
Bin Yang, Wenjie Luo, Raquel Urtasun, 
CVPR, 2018  :star:
- [Deep continuous fusion for multi-sensor 3d object detection](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ming_Liang_Deep_Continuous_Fusion_ECCV_2018_paper.pdf), 
Ming Liang, Bin Yang, Shenlong Wang, and Raquel Urtasun, 
ECCV, 2018  :star:



## PointNet
- [Pointnet: Deep learning on point sets for 3d classification and segmentation](https://arxiv.org/abs/1612.00593), 
Charles R. Qi*, Hao Su*, Kaichun Mo, Leonidas J. Guibas, 
[code](https://github.com/charlesq34/pointnet), 
[website](http://stanford.edu/~rqi/pointnet/), 
CVPR, 2017  :star:
- [Pointnet++: Deep hierarchical feature learning on point sets in a metric space](https://arxiv.org/abs/1706.02413), 
Charles R. Qi, Li (Eric) Yi, Hao Su, Leonidas J. Guibas, 
[code](https://github.com/charlesq34/pointnet2), 
[website](http://stanford.edu/~rqi/pointnet2/), 
NIPS, 2017
- [Frustum pointnets for 3d object detection from rgb-d data](https://arxiv.org/abs/1711.08488), 
Charles R. Qi, Wei Liu, Chenxia Wu, Hao Su, Leonidas J. Guibas, 
[code](https://github.com/charlesq34/frustum-pointnets), 
[website](http://stanford.edu/~rqi/frustum-pointnets/), 
CVPR, 2018  :star:
- [PointRCNN 3D Object Proposal Generation and Detection from Point Cloud](https://arxiv.org/pdf/1812.04244.pdf), 
Shaoshuai Shi, Xiaogang Wang, Hongsheng Li, 
2018  :star:
- [Pointfusion: Deep sensor fusion for 3d bounding box estimation](https://arxiv.org/pdf/1711.10871.pdf), 
Danfei Xu, Dragomir Anguelov, Ashesh Jain, 
CVPR, 2018
- [Voxelnet: End-to-end learning for point cloud based 3d object detection](https://arxiv.org/pdf/1711.06396.pdf), 
Yin Zhou, Oncel Tuzel, 
[unofficial code](https://github.com/jeasinema/VoxelNet-tensorflow), 
CVPR, 2018  :star:
- [Second: Sparsely embedded convolutional detection](https://pdfs.semanticscholar.org/5125/a16039cabc6320c908a4764f32596e018ad3.pdf), 
Yan Yan,, Yuxing Mao, and Bo Li, 
[code](https://github.com/traveller59/second.pytorch), 
Sensors, 2018
- [Pointpillars: Encoders for object detection from point clouds](https://arxiv.org/pdf/1812.05784.pdf), 
Alex H. Lang, Sourabh Vora, Holger Caesar, Lubing Zhou, Jiong Yang, Oscar Beijbom, 
[code](https://github.com/nutonomy/second.pytorch), 
2018
- [RoarNet: A Robust 3D Object Detection based on RegiOn Approximation Refinement](https://arxiv.org/pdf/1811.03818), 
Kiwoo Shin, Youngwook Paul Kwon, Masayoshi Tomizuka, 
[code](https://github.com/Kiwoo/RoarNet), 
2018  :star:
- [IPOD: Intensive Point-based Object Detector for Point Cloud](https://arxiv.org/pdf/1812.05276.pdf), 
Zetong Yang, Yanan Sun, Shu Liu, Xiaoyong Shen, Jiaya Jia, 
2018
- [Frustum ConvNet: Sliding Frustums to Aggregate Local Point-Wise Features for Amodal 3D Object Detection](https://arxiv.org/pdf/1903.01864.pdf), 
Zhixin Wang, Kui Jia, 
2019  :star:
- [3D Object Detection Using Scale Invariant and Feature Reweighting Networks](https://arxiv.org/pdf/1711.10871.pdf), 
Xin Zhao, Zhe Liu, Ruolan Hu, Kaiqi Huang, 
AAAI, 2019
- [STD: Sparse-to-Dense 3D Object Detector for Point Cloud](https://arxiv.org/pdf/1907.10471.pdf)Zetong Yang, Yanan Sun, Shu Liu, Xiaoyong Shen, Jiaya Jia, 
ICCV, 2019  :star:

## Other
- [Recurrent slice networks for 3d segmentation of point clouds](https://arxiv.org/pdf/1802.04402.pdf), 
Qiangui Huang, Weiyue Wang, Ulrich Neumann, 
[code](https://github.com/qianguih/RSNet), 
CVPR, 2018  :star:
- [Part-A^2 Net: 3D Part-Aware and Aggregation Neural Network for Object Detection from Point Cloud](https://arxiv.org/pdf/1907.03670.pdf),Shaoshuai Shi, Zhe Wang, Xiaogang Wang, Hongsheng Li, 
2019  :star:
- [Multi-Task Multi-Sensor Fusion for 3D Object Detection](http://openaccess.thecvf.com/content_CVPR_2019/papers/Liang_Multi-Task_Multi-Sensor_Fusion_for_3D_Object_Detection_CVPR_2019_paper.pdf), 
Ming Liang, Bin Yang, Yun Chen, Rui Hu, Raquel Urtasun,
2019, :star:
- [Generalized Intersection over Union: A Metric and A Loss for Bounding Box Regression](https://arxiv.org/pdf/1902.09630.pdf),
Hamid Rezatofighi, Nathan Tsoi1, JunYoung Gwak, Amir Sadeghian, Ian Reid, Silvio Savarese,
2019, :star:
- [Voxel-FPN: multi-scale voxel feature aggregationin 3D object detection from point clouds](https://arxiv.org/ftp/arxiv/papers/1907/1907.05286.pdf),
Bei Wang, Jianping An and Jiayan Cao,
2019, :star:
- [Pointsift: A sift-like network module for 3d point cloud semantic segmentation](https://arxiv.org/abs/1807.00652), 
Mingyang Jiang, Yiran Wu, Tianqi Zhao, Zelin Zhao, Cewu Lu, 
[code](https://github.com/MVIG-SJTU/pointSIFT), 
CoRR, 2018
- [PointRCNN: 3D Object Proposal Generation and Detection from Point Cloud](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_PointRCNN_3D_Object_Proposal_Generation_and_Detection_From_Point_Cloud_CVPR_2019_paper.pdf),
Shaoshuai Shi, Xiaogang Wang, Hongsheng Li,
2019
- [Fast Point R-CNN](https://arxiv.org/pdf/1908.02990.pdf),
Yilun Chen, Shu Liu, Xiaoyong Shen, Jiaya Jia
2019


## my reading list
- 3D Backbone Network for 3D Object Detection, 2019
- A General Pipeline for 3D Detection of Vehicles, 2018



## active researchers
- [Bo Li](http://prclibo.github.io/)
- [Hao Su](http://cseweb.ucsd.edu/~haosu/index.html#teaching)
- [Charles Ruizhongtai Qi](http://stanford.edu/~rqi/)
- [Bin Yang](http://www.cs.toronto.edu/~byang/)
