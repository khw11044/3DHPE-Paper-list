# Papers of 3D human Pose Estimation via Multi-view 


## Dataset 

### Human3.6M

<https://paperswithcode.com/dataset/human3-6m>

![fig1](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/32afc7c3-3a66-4813-9e9b-736354a6df26/Untitled.png)

![fig2](https://user-images.githubusercontent.com/831215/47666702-83f82f80-dba4-11e8-89b8-9fd029189ba2.png)

3.6 million개의 human poses

The Human3.6M dataset is one of the largest motion capture datasets, which consists of 3.6 million human poses and corresponding images captured by a high-speed motion capture system.

4개의 카메라 

**구성**

Video, Segments, Features, Depth, Scanner, Poses

**17개의 시나리오**

Directions, Discussion, Eating, Greeting, Phone Call, Posing, Purchases, Sitting, Sitting Down, Smoking, Taking Photo, Waiting, Walking, Walking Dog, Walking Together

**Training Data**

Subject : S1,S5,S6,S7,S8,S9,S11

128*7 개의 training video

**Testing Data**

Subject: S2,S3,S4,S10

128*4 개의 training video

**32개의 joint**


### MPI-INF-3DHP

<https://paperswithcode.com/dataset/mpi-inf-3dhp>

![fig3](https://www.researchgate.net/profile/Sandika-Biswas-2/publication/336161944/figure/fig2/AS:845671196274688@1578635133172/Left-Image-from-MPI-INF-3dHP-test-dataset-Right-Comparison-of-2d-ground-truth-pose.png)

MPI-INF-3DHP is a 3D human body pose estimation dataset consisting of both constrained indoor and complex outdoor scenes.

8명의 actors, 8개의 subjects 14개의 카메라 

s1,s2,s3,s4,s5,s6,s7,s8 각각 seq1과 seq2가 있다.

8*2*14개의 video

**28개의 joint**

### CMU Panoptic 

multi person 

500+ views

60+ subjects

180+ social game sequences from 120+ subjects

### SkiPose-PTZ


---

## Multi-view 3D human pose estimation with 3D annotation 

🔗 **Learnable Triagulation of Human Pose**

Samsung AI Center, Moscow  
Skolkovo Institute of Science and Technology, Moscow

ICCV 2019

- [paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Iskakov_Learnable_Triangulation_of_Human_Pose_ICCV_2019_paper.pdf)

- [code](https://github.com/karfly/learnable-triangulation-pytorch)


🔗 **Cross View Fusion for 3D Human Pose Estimation**

Microsoft Research Asia

ICCV 2019

- [paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Qiu_Cross_View_Fusion_for_3D_Human_Pose_Estimation_ICCV_2019_paper.pdf)

- [code](https://github.com/microsoft/multiview-human-pose-estimation-pytorch)


🔗 **Epipolar Transformer**

Carnegi Mellon University, Facebook Reality Labs

CVPR 2020

- [paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/He_Epipolar_Transformers_CVPR_2020_paper.pdf)

- [code](https://github.com/yihui-he/epipolar-transformers)

🔗 **3D human pose estimation in video with temporal convolutions and semi-supervised training**

Facebook AI Research, Google Brain

CVPR 2019

- [paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Pavllo_3D_Human_Pose_Estimation_in_Video_With_Temporal_Convolutions_and_CVPR_2019_paper.pdf)

- [code](https://github.com/facebookresearch/VideoPose3D)

---

## Multi-view 3D human pose estimation without 3D annotation 
(= Weakly-supervised 3D Human Pose Estimation)

🔗 **Self-Supervised Learning of 3D Human Pose using Multi-view Geometry**

: EpipolarPose

Department of Computer Engineering, Middle East Technical University

CVPR 2019

- [paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kocabas_Self-Supervised_Learning_of_3D_Human_Pose_Using_Multi-View_Geometry_CVPR_2019_paper.pdf)

- [code](https://github.com/mkocabas/EpipolarPose)

🔗 **Weakly-Supervised 3D Human Pose Learning via Multi-view Images in the Wild**

NVIDIA

CVPR 2020

- [paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Iqbal_Weakly-Supervised_3D_Human_Pose_Learning_via_Multi-View_Images_in_the_CVPR_2020_paper.pdf)

- code 없음 

🔗 **CanonPose: Self-Supervised Monocular 3D Human Pose Estimation in the Wild**

Leibniz University Hannover, Hannover, Germany
University of British Columbia, Vancouver, Canada

CVPR 2021

- [paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Wandt_CanonPose_Self-Supervised_Monocular_3D_Human_Pose_Estimation_in_the_Wild_CVPR_2021_paper.pdf)

- [code](https://github.com/bastianwandt/CanonPose)

🔗 **MetaPose: Fast 3D Pose from Multiple Views without 3D Supervision**

Boston University, Google Research, University of Toronto, MIT-IBM Waston AI Lab

ICCV 제출

- [paper](https://arxiv.org/pdf/2108.04869v1.pdf)

- code 없음 

🔗 **RepNet: Weakly Supervised Training of an Adversarial Reprojection Network for 3D Human Pose Estimation**

Bastian Wandt and Bodo Rosenhahn
Leibniz Universitat Hannover 
Hannover, Germany

CVPR 2019

- [paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wandt_RepNet_Weakly_Supervised_Training_of_an_Adversarial_Reprojection_Network_for_CVPR_2019_paper.pdf)

- [code](https://github.com/bastianwandt/RepNet)

---

## The others

[surveyofHumanPoseEstimation](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9144178)

[BodyPoseNet](https://eehoeskrap.tistory.com/564)
2D pose estimation 

[Canonical](Canonical Capsules: Unsupervised Capsules in Canonical Pose)