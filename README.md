# Awesome Human Pose Estimation with stars

<p align="center">
  <img src="diagram_2.png" width=700>
</p>

A collection of resources on Human Pose Estimation.

## Why awesome human pose estimation?

This is a collection of papers and resources I curated when learning the ropes in Human Pose estimation. I will be continuously updating this list with the latest papers and resources. If you want to learn the basics of Human Pose Estimation and understand how the field has evolved, check out these articles I published on [2D Pose Estimation](https://blog.nanonets.com/human-pose-estimation-2d-guide/?utm_source=github\&utm_medium=social\&utm_campaign=pose\&utm_content=cbsudux) and [3D Pose Estimation](https://blog.nanonets.com/human-pose-estimation-3d-guide/)

## Contributing

If you think I have missed out on something (or) have any suggestions (papers, implementations and other resources), feel free to [pull a request](https://github.com/cbsudux/awesome-human-pose-estimation/pulls) ⭐ 2,480 | 🐛 7 | 📅 2022-10-12

Feedback and contributions are welcome!

## Table of Contents

* [Basics](#basics)
* [Papers](#papers)
  * [2D Pose estimation](#2d-pose-estimation)
  * [3D Pose estimation](#3d-pose-estimation)
  * [Person generation](#person-generation)
  * [Real-time Pose estimation](#real-time-pose-estimation)
* [Datasets](#datasets)
* [Workshops](#workshops)
* [Blog posts](#blogposts)
* [Popular implementations](#popular-implementations)
  * [PyTorch](#pytorch)
  * [TensorFlow](#tensorflow)
  * [Torch](#Torch)
  * [Others](#others)

## Basics

* [A 2019 guide to Human Pose Estimation with Deep Learning](https://blog.nanonets.com/human-pose-estimation-2d-guide/?utm_source=reddit\&utm_medium=social\&utm_campaign=pose\&utm_content=GROUP_NAME)

## Papers

### 2D Pose estimation

* [Realtime Multi-person 2D Pose Estimation Using Part Affinity Fields](https://arxiv.org/pdf/1611.08050.pdf) - [\[CODE\]](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation) ⭐ 5,123 | 🐛 107 | 🌐 Jupyter Notebook | 📅 2020-03-21 - Cao, Z., Simon, T., Wei, S., & Sheikh, Y. (CVPR 2017)
* [Deep High-Resolution Representation Learning for Human Pose Estimation](https://arxiv.org/abs/1902.09212) - [\[CODE\]](https://github.com/leoxiaobin/deep-high-resolution-net.pytorch) ⭐ 4,480 | 🐛 209 | 🌐 Cuda | 📅 2024-08-30 Ke Sun, Bin Xiao, Dong Liu, Jingdong Wang (CVPR 2019)
* [Simple Baselines for Human Pose Estimation
  and Tracking](http://openaccess.thecvf.com/content_ECCV_2018/papers/Bin_Xiao_Simple_Baselines_for_ECCV_2018_paper.pdf) - [\[CODE\]](https://github.com/Microsoft/human-pose-estimation.pytorch) ⚠️ Archived - Bin, Xiao, Haiping Wu, Yichen Wei (ECCV 2018)
* [Real-time 2D Multi-Person Pose Estimation on CPU: Lightweight OpenPose](https://arxiv.org/pdf/1811.12004.pdf) - [\[CODE\]](https://github.com/Daniil-Osokin/lightweight-human-pose-estimation.pytorch) ⭐ 2,241 | 🐛 2 | 🌐 Python | 📅 2024-04-30 Osokin, D. (ArXiv 2018)
* [Convolutional Pose Machines](https://arxiv.org/pdf/1602.00134.pdf) - [\[CODE\]](https://github.com/shihenw/convolutional-pose-machines-release) ⭐ 883 | 🐛 45 | 🌐 Jupyter Notebook | 📅 2018-06-05 - Wei, S., Ramakrishna, V., Kanade, T., & Sheikh, Y. (CVPR 2016)
* [Stacked Hourglass Networks for Human Pose Estimation](https://arxiv.org/pdf/1603.06937.pdf) - [\[CODE\]](https://github.com/umich-vl/pose-hg-demo) ⭐ 314 | 🐛 17 | 🌐 Lua | 📅 2017-10-17 - Newell, A., Yang, K., & Deng, J. (ECCV 2016)
* [LSTM Pose Machines](https://arxiv.org/pdf/1712.06316.pdf) - [\[CODE\]](https://github.com/lawy623/LSTM_Pose_Machines) ⭐ 276 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2019-02-20 - Yue Luo, Jimmy Ren, Zhouxia Wang, Wenxiu Sun, Jinshan Pan, Jianbo Liu, Jiahao Pang, Liang Lin (CVPR 2018)
* [DeepCut: Joint Subset Partition and Labeling for Multi Person Pose Estimation](https://arxiv.org/pdf/1511.06645.pdf) - [\[CODE\]](https://github.com/eldar/deepcut) ⭐ 222 | 🐛 10 | 🌐 Matlab | 📅 2016-08-30 - Pishchulin, L., Insafutdinov, E., Tang, S., Andres, B., Andriluka, M., Gehler, P.V., & Schiele, B. (CVPR 2016)
* [Learning Feature Pyramids for Human Pose Estimation](https://arxiv.org/pdf/1708.01101.pdf) - [\[CODE\]](https://github.com/bearpaw/PyraNet) ⭐ 221 | 🐛 11 | 🌐 Lua | 📅 2021-12-20 - Yang, W., Li, S., Ouyang, W., Li, H., & Wang, X. (ICCV 2017)
* [DeeperCut: A Deeper, Stronger, and Faster Multi-Person Pose Estimation Model](https://arxiv.org/pdf/1605.03170.pdf) - [\[CODE1\]](https://github.com/eldar/deepcut-cnn) ⭐ 191 | 🐛 19 | 🌐 C++ | 📅 2017-11-08[\[CODE2\]](https://github.com/eldar/pose-tensorflow) ⭐ 1,141 | 🐛 65 | 🌐 C++ | 📅 2019-12-07 - Insafutdinov, E., Pishchulin, L., Andres, B., Andriluka, M., & Schiele, B. (ECCV 2016)
* [Multi-context Attention for Human Pose Estimation](https://arxiv.org/pdf/1702.07432.pdf) - [\[CODE\]](https://github.com/bearpaw/pose-attention) ⭐ 173 | 🐛 5 | 🌐 Lua | 📅 2021-12-20 - Chu, X., Yang, W., Ouyang, W., Ma, C., Yuille, A.L., & Wang, X. (CVPR 2017)
* [Flowing ConvNets for Human Pose Estimation in Videos](https://arxiv.org/pdf/1506.02897.pdf) - [\[CODE\]](https://github.com/tpfister/caffe-heatmap) ⭐ 166 | 🐛 14 | 🌐 C++ | 📅 2017-07-22 - Pfister, T., Charles, J., & Zisserman, A. (ICCV 2015)
* [Towards Accurate Multi-person Pose Estimation in the Wild](https://arxiv.org/pdf/1701.01779.pdf) - [\[CODE\]](https://github.com/hackiey/keypoints) ⭐ 104 | 🐛 4 | 🌐 Python | 📅 2019-04-15 - Papandreou, G., Zhu, T., Kanazawa, N., Toshev, A., Tompson, J., Bregler, C., & Murphy, K.P. (CVPR 2017)
* [RMPE: Regional Multi-person Pose Estimation](https://arxiv.org/pdf/1612.00137.pdf) - [\[CODE1\]](https://github.com/Fang-Haoshu/RMPE) ⭐ 96 | 🐛 1 | 🌐 C++ | 📅 2018-09-01[\[CODE2\]](https://github.com/MVIG-SJTU/AlphaPose) ⭐ 8,593 | 🐛 304 | 🌐 Python | 📅 2024-05-13 - Fang, H., Xie, S., & Lu, C. (ICCV 2017)
* [Knowledge-Guided Deep Fractal Neural Networks for Human Pose Estimation](https://arxiv.org/pdf/1705.02407.pdf) - [\[CODE\]](https://github.com/Guanghan/GNet-pose) ⭐ 88 | 🐛 7 | 🌐 Matlab | 📅 2018-09-27 Ning, G., Zhang, Z., & He, Z. (IEEE Transactions on Multimedia 2018)
* [Human Pose Estimation with Iterative Error Feedback](https://arxiv.org/pdf/1507.06550.pdf)- [\[CODE\]](https://github.com/pulkitag/ief) ⭐ 57 | 🐛 8 | 🌐 Python | 📅 2016-10-13 Carreira, J., Agrawal, P., Fragkiadaki, K., & Malik, J. (CVPR 2016)
* [Joint Training of a Convolutional Network and a Graphical Model for Human Pose Estimation](https://arxiv.org/pdf/1406.2984.pdf) - [\[CODE\]](https://github.com/max-andr/joint-cnn-mrf) ⭐ 55 | 🐛 2 | 🌐 Python | 📅 2018-02-25 - Tompson, J., Jain, A., LeCun, Y., & Bregler, C. (NIPS 2014)
* [Self Adversarial Training for Human Pose Estimation](https://arxiv.org/pdf/1707.02439.pdf) - [\[CODE1\]](https://github.com/dongzhuoyao/jessiechouuu-adversarial-pose) ⭐ 31 | 🐛 0 | 🌐 Lua | 📅 2017-10-23[\[CODE2\]](https://github.com/roytseng-tw/adversarial-pose-pytorch) ⭐ 66 | 🐛 0 | 🌐 Python | 📅 2018-01-24 - Chou, C., Chien, J., & Chen, H. (ArXiv 2017)
* [Learning Human Pose Estimation Features with Convolutional Networks](https://arxiv.org/pdf/1312.7302.pdf) - Jain, A., Tompson, J., Andriluka, M., Taylor, G.W., & Bregler, C. (ICLR 2013)
* [DeepPose: Human Pose Estimation via Deep Neural Networks](https://arxiv.org/pdf/1312.4659.pdf) - Toshev, A., & Szegedy, C. (CVPR 2014)
* [MoDeep: A Deep Learning Framework Using Motion Features for Human Pose Estimation](https://arxiv.org/pdf/1409.7963.pdf) - Jain, A., Tompson, J., LeCun, Y., & Bregler, C. (ACCV 2014)
* [Efficient Object Localization Using Convolutional Networks](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.858.5872\&rep=rep1\&type=pdf) - Tompson, J., Goroshin, R., Jain, A., LeCun, Y., & Bregler, C (CVPR 2015)
* [Human Pose Estimation Using Global and Local Normalization](https://arxiv.org/pdf/1709.07220.pdf) - Sun, K., Lan, C., Xing, J., Zeng, W., Liu, D., & Wang, J. (ICCV 2017)
* [Adversarial PoseNet: A Structure-Aware Convolutional Network for Human Pose Estimation](https://arxiv.org/pdf/1705.00389.pdf) - Chen, Y., Shen, C., Wei, X., Liu, L., & Yang, J. (ICCV 2017)
* [Recurrent Human Pose Estimation](https://arxiv.org/pdf/1605.02914.pdf) - [\[CODE\]](https://github.com/ox-vgg/keypoint_detection) - Belagiannis, V., & Zisserman, A. (FG 2017)
* [Human Pose Estimation with Parsing Induced Learner](http://openaccess.thecvf.com/content_cvpr_2018/papers/Nie_Human_Pose_Estimation_CVPR_2018_paper.pdf)- Xuecheng Nie, Jiashi Feng, Yiming Zuo, Shuicheng Yan (CVPR 2018)
* [Multi-Scale Structure-Aware Network for Human Pose Estimation](http://openaccess.thecvf.com/content_ECCV_2018/papers/Lipeng_Ke_Multi-Scale_Structure-Aware_Network_ECCV_2018_paper.pdf) - Lipeng Ke, Ming-Ching Chang, Honggang Qi, Siwei Lyu (ECCV 2018)
* [Deeply Learned Compositional Models for Human Pose Estimation](http://openaccess.thecvf.com/content_ECCV_2018/papers/Wei_Tang_Deeply_Learned_Compositional_ECCV_2018_paper.pdf) - Wei Tang, Pei Yu, Ying Wu (ECCV 2018)

### 3D Pose estimation

* [Dense Human Pose Estimation In The Wild](https://arxiv.org/pdf/1802.00434.pdf) - [\[CODE\]](https://github.com/facebookresearch/Densepose) ⚠️ Archived - Guler, R.A., Neverova, N., & Kokkinos, I. (ArXiv 2018)
* [3D human pose estimation in video with temporal convolutions and
  semi-supervised training](https://arxiv.org/pdf/1811.11742.pdf) - [\[CODE\]](https://github.com/facebookresearch/VideoPose3D) ⚠️ Archived - Pavllo, D., Feichtenhofer, C., Grangier, D., & Auli, M (ArXiv 2018)
* [End-to-end Recovery of Human Shape and Pose](https://arxiv.org/pdf/1712.06584.pdf) - [\[CODE\]](https://github.com/akanazawa/hmr) ⭐ 1,666 | 🐛 19 | 🌐 Python | 📅 2023-07-10 - Kanazawa, A., Black, M.J., Jacobs, D.W., & Malik, J. (CVPR 2018)
* [Single-Shot Multi-Person 3D Pose Estimation From Monocular RGB](https://arxiv.org/pdf/1712.03453.pdf) - [\[CODE1\]](http://gvv.mpi-inf.mpg.de/projects/SingleShotMultiPerson/)[\[CODE2\]](https://github.com/Daniil-Osokin/lightweight-human-pose-estimation-3d-demo.pytorch) ⭐ 688 | 🐛 3 | 🌐 Python | 📅 2023-11-25 - Mehta, D.,  Sotnychenko, O., Mueller, F., Xu, W., Sridhar, S., Pons-Moll, G., Theobalt, C. (3DV 2018)
* [Towards 3D Human Pose Estimation in the Wild: a Weakly-supervised Approach](https://arxiv.org/pdf/1704.02447.pdf) - [\[CODE\]](https://github.com/xingyizhou/Pytorch-pose-hg-3d) ⭐ 612 | 🐛 36 | 🌐 Python | 📅 2023-06-21 - Zhou, X., Huang, Q., Sun, X., Xue, X., & Wei, Y. (ICCV 2017)
* [Integral Human Pose Regression](https://arxiv.org/pdf/1711.08229.pdf) - [\[CODE\]](https://github.com/JimmySuen/integral-human-pose) ⭐ 488 | 🐛 10 | 🌐 Cuda | 📅 2019-04-04 - Sun, X., Xiao, B., Liang, S., & Wei, Y. (ECCV 2018)
* [VNect: Real-time 3D Human Pose Estimation with a Single RGB Camera](http://gvv.mpi-inf.mpg.de/projects/VNect/content/VNect_SIGGRAPH2017.pdf) - [\[CODE\]](https://github.com/timctho/VNect-tensorflow) ⭐ 473 | 🐛 17 | 🌐 Python | 📅 2019-01-09 - Mehta, Dushyant et al. (SIGGRAPH 2017)
* [Neural Body Fitting: Unifying Deep Learning and Model-Based Human Pose and Shape Estimation](https://arxiv.org/pdf/1808.05942.pdf) - [\[CODE\]](https://github.com/mohomran/neural_body_fitting) ⭐ 272 | 🐛 14 | 🌐 Python | 📅 2018-10-23 - Omran, Mohamed and Lassner, Christoph and Pons-Moll, Gerard and Gehler, Peter V. and Schiele, Bernt (3DV 2018)
* [BodyNet: Volumetric Inference of 3D Human Body Shapes](https://arxiv.org/pdf/1804.04875v3.pdf) - [\[CODE\]](https://github.com/gulvarol/bodynet) ⭐ 263 | 🐛 5 | 🌐 Lua | 📅 2018-09-06 - Varol, G., Ceylan, D., Russell, B., Yang, J., Yumer, E., Laptev, I., & Schmid, C. (ECCV 2018)
* [Unsupervised Geometry-Aware Representation for 3D Human Pose Estimation](http://openaccess.thecvf.com/content_ECCV_2018/papers/Helge_Rhodin_Unsupervised_Geometry-Aware_Representation_ECCV_2018_paper.pdf) - [\[CODE\]](https://github.com/hrhodin/UnsupervisedGeometryAwareRepresentationLearning) ⭐ 124 | 🐛 0 | 🌐 Python | 📅 2019-11-09 - Rhodin, H., Salzmann, M., & Fua, P. (ECCV 2018)
* [Coarse-to-Fine Volumetric Prediction for Single-Image 3D Human Pose](https://arxiv.org/pdf/1611.07828.pdf) - [\[CODE\]](https://github.com/geopavlakos/c2f-vol-demo) ⭐ 81 | 🐛 6 | 🌐 Lua | 📅 2017-07-10 - Pavlakos, G., Zhou, X., Derpanis, K.G., & Daniilidis, K. (CVPR 2017)
* [3D Human Pose Estimation from Monocular Images with Deep Convolutional Neural Network](http://visal.cs.cityu.edu.hk/static/pubs/conf/accv14-3dposecnn.pdf) - Li, S., & Chan, A.B. (ACCV 2014)
* [Structured Prediction of 3D Human Pose with Deep Neural Networks](https://arxiv.org/pdf/1605.05180.pdf) - Tekin, B., Katircioglu, I., Salzmann, M., Lepetit, V., & Fua, P. (BMVC 2016)
* [Recurrent 3D Pose Sequence Machines](https://arxiv.org/pdf/1707.09695.pdf) - Lin, M., Lin, L., Liang, X., Wang, K., & Cheng, H. (CVPR 2017)
* [Lifting from the Deep: Convolutional 3D Pose Estimation from a Single Image](https://arxiv.org/pdf/1701.00295.pdf) - Tomè, D., Russell, C., & Agapito, L. (CVPR 2017)
* [A Simple Yet Effective Baseline for 3d Human Pose Estimation](https://arxiv.org/pdf/1705.03098.pdf) - Martinez, J., Hossain, R., Romero, J., & Little, J.J. (ICCV 2017)
* [Compositional Human Pose Regression](https://arxiv.org/pdf/1704.00159.pdf) - Sun, X., Shang, J., Liang, S., & Wei, Y. (ICCV 2017)
* [Monocular 3D Human Pose Estimation In The Wild Using Improved CNN Supervision](http://gvv.mpi-inf.mpg.de/3dhp-dataset/) - Mehta, D., Rhodin, H., Casas, D., Fua, P., Sotnychenko, O., Xu, W., & Theobalt, C. (3DV 2017)
* [3D Human Pose Estimation in the Wild by Adversarial Learning](https://arxiv.org/pdf/1803.09722.pdf) - Yang, W., Ouyang, W., Wang, X., Ren, J.S., Li, H., & Wang, X. (2018)
* [DRPose3D: Depth Ranking in 3D Human Pose Estimation](https://arxiv.org/pdf/1805.08973.pdf) - Wang, M., Chen, X., Liu, W., Qian, C., Lin, L., & Ma, L. (IJCAI 2018)
* [Learning to Estimate 3D Human Pose and Shape from a Single Color Image](http://openaccess.thecvf.com/content_cvpr_2018/papers/Pavlakos_Learning_to_Estimate_CVPR_2018_paper.pdf) - Pavlakos, G., Zhu, L., Zhou, X., & Daniilidis, K. (CVPR 2018)
* [Learning 3D Human Pose from Structure and Motion](http://openaccess.thecvf.com/content_ECCV_2018/papers/Rishabh_Dabral_Learning_3D_Human_ECCV_2018_paper.pdf) - Dabral, R., Mundhada, A., Kusupati, U., Afaque, S., Sharma, A., & Jain, A. (ECCV 2018)
* [Dense Pose Transfer](https://arxiv.org/pdf/1809.01995.pdf) - Neverova, N., Guler, R.A., & Kokkinos, I. (ECCV 2018)

### Person generation

* [Deformable GANs for Pose-based Human Image Generation](http://openaccess.thecvf.com/content_cvpr_2018/papers/Siarohin_Deformable_GANs_for_CVPR_2018_paper.pdf) - [\[CODE\]](https://github.com/AliaksandrSiarohin/pose-gan) ⭐ 392 | 🐛 18 | 🌐 Python | 📅 2023-04-05 - Siarohin, A., Sangineto, E., Lathuilière, S., & Sebe, N. (CVPR 2018)
* [Pose Guided Person Image Generation](https://arxiv.org/pdf/1705.09368.pdf) - [\[CODE\]](https://github.com/charliememory/Pose-Guided-Person-Image-Generation) ⭐ 302 | 🐛 18 | 🌐 Python | 📅 2023-08-11 - Ma, L., Jia, X., Sun, Q., Schiele, B., Tuytelaars, T., & Gool, L.V. (NIPS 2017)
* [A Generative Model of People in Clothing](https://arxiv.org/pdf/1705.04098.pdf) - Lassner, C., Pons-Moll, G., & Gehler, P.V. (ICCV 2017)
* [Dense Pose Transfer](https://arxiv.org/pdf/1809.01995.pdf) - Neverova, N., Guler, R.A., & Kokkinos, I. (ECCV 2018)

### Real-time pose estimation

* [Dense Human Pose Estimation In The Wild](https://arxiv.org/pdf/1802.00434.pdf) - [\[CODE\]](https://github.com/facebookresearch/Densepose) ⚠️ Archived - Guler, R.A., Neverova, N., & Kokkinos, I. (ArXiv 2018)
* [Realtime Multi-person 2D Pose Estimation Using Part Affinity Fields](https://arxiv.org/pdf/1611.08050.pdf) - [\[CODE\]](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation) ⭐ 5,123 | 🐛 107 | 🌐 Jupyter Notebook | 📅 2020-03-21 - Cao, Z., Simon, T., Wei, S., & Sheikh, Y. (CVPR 2017)
* [Real-time 2D Multi-Person Pose Estimation on CPU: Lightweight OpenPose](https://arxiv.org/pdf/1811.12004.pdf) - [\[CODE\]](https://github.com/Daniil-Osokin/lightweight-human-pose-estimation.pytorch) ⭐ 2,241 | 🐛 2 | 🌐 Python | 📅 2024-04-30 Osokin, D. (ArXiv 2018)
  * Extension to 3D pose estimation (based on [Single-Shot Multi-Person 3D Pose Estimation From Monocular RGB](https://arxiv.org/pdf/1712.03453.pdf) - Mehta, D., et al.) - [\[CODE\]](https://github.com/Daniil-Osokin/lightweight-human-pose-estimation-3d-demo.pytorch) ⭐ 688 | 🐛 3 | 🌐 Python | 📅 2023-11-25
* [VNect: Real-time 3D Human Pose Estimation with a Single RGB Camera](http://gvv.mpi-inf.mpg.de/projects/VNect/content/VNect_SIGGRAPH2017.pdf) - [\[CODE\]](https://github.com/timctho/VNect-tensorflow) ⭐ 473 | 🐛 17 | 🌐 Python | 📅 2019-01-09 - Mehta, Dushyant et al. (SIGGRAPH 2017)
* [RMPE: Regional Multi-person Pose Estimation](https://arxiv.org/pdf/1612.00137.pdf) - [\[CODE1\]](https://github.com/Fang-Haoshu/RMPE) ⭐ 96 | 🐛 1 | 🌐 C++ | 📅 2018-09-01[\[CODE2\]](https://github.com/MVIG-SJTU/AlphaPose) ⭐ 8,593 | 🐛 304 | 🌐 Python | 📅 2024-05-13 - Fang, H., Xie, S., & Lu, C. (ICCV 2017)

## Datasets

### 2D

* [MPII Human Pose Dataset](http://human-pose.mpi-inf.mpg.de/)
* [LSP](http://sam.johnson.io/research/lsp.html)
* [FLIC](https://bensapp.github.io/flic-dataset.html)
* [FLIC-plus](https://cims.nyu.edu/~tompson/flic_plus.htm)

### 3D

* [Human3.6M](http://vision.imar.ro/human3.6m/description.php)
* [HumanEva](http://humaneva.is.tue.mpg.de/)
* [MPI-INF-3DHP](http://gvv.mpi-inf.mpg.de/3dhp-dataset/)
* [Unite The People](http://files.is.tuebingen.mpg.de/classner/up/)

## Workshops

* [POSETRACK-ECCV](https://posetrack.net/workshops/eccv2018/)
* [3D HUMANS-CVPR 2018](https://project.inria.fr/humans2018/)

## Blog posts

* [Real-time Human Pose Estimation in the Browser with TensorFlow.js](https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5)
* [Deep learning for human pose estimation](https://www.slideshare.net/plutoyang/mmlab-seminar-2016-deep-learning-for-human-pose-estimation)
* [Deep Learning based Human Pose Estimation using OpenCV ( C++ / Python )](https://www.learnopencv.com/deep-learning-based-human-pose-estimation-using-opencv-cpp-python/)

## Popular implementations

### PyTorch

* [AlphaPose](https://github.com/MVIG-SJTU/AlphaPose/tree/pytorch) ⭐ 8,593 | 🐛 304 | 🌐 Python | 📅 2024-05-13
* [deep-high-resolution-net.pytorch](https://github.com/leoxiaobin/deep-high-resolution-net.pytorch) ⭐ 4,480 | 🐛 209 | 🌐 Cuda | 📅 2024-08-30
* [human-pose-estimation.pytorch](https://github.com/Microsoft/human-pose-estimation.pytorch) ⚠️ Archived
* [pytorch\_Realtime\_Multi-Person\_Pose\_Estimation](https://github.com/tensorboy/pytorch_Realtime_Multi-Person_Pose_Estimation) ⭐ 1,371 | 🐛 62 | 🌐 Python | 📅 2023-02-07
* [pytorch-pose](https://github.com/bearpaw/pytorch-pose) ⭐ 1,121 | 🐛 32 | 🌐 Python | 📅 2021-12-20
* [pytorch-pose-hg-3d](https://github.com/xingyizhou/Pytorch-pose-hg-3d) ⭐ 612 | 🐛 36 | 🌐 Python | 📅 2023-06-21
* [3d\_pose\_baseline\_pytorch](https://github.com/weigq/3d_pose_baseline_pytorch) ⚠️ Archived

### TensorFlow

* [pose-tensorflow](https://github.com/eldar/pose-tensorflow) ⭐ 1,141 | 🐛 65 | 🌐 C++ | 📅 2019-12-07
* [tf-pose-estimation](https://github.com/ildoonet/tf-pose-estimation)

### Torch

* [pose-hg-train](https://github.com/umich-vl/pose-hg-train) ⭐ 576 | 🐛 26 | 🌐 Jupyter Notebook | 📅 2017-04-13
* [pose-hg-demo](https://github.com/umich-vl/pose-hg-demo) ⭐ 314 | 🐛 17 | 🌐 Lua | 📅 2017-10-17

### Others

* [openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) ⭐ 34,393 | 🐛 359 | 🌐 C++ | 📅 2024-08-03
* [DensePose](https://github.com/facebookresearch/DensePose) ⚠️ Archived

## Todo

* [x] Add basics
* [ ] Add papers on Person Re-Identification
* [ ] Add papers on Multi Person Pose estimation
* [ ] Add a SOTA ranking

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
