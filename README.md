# SOTA-MedReg
State-of-the-art medical image registration methods



## [CuRIOUS](https://curious2019.grand-challenge.org/Home/)

> Summary paper: [TMI](https://ieeexplore.ieee.org/document/8795512)

### Register pre-operative MRI to iUS before tumor resection

|First Author|Method|Training|Testing|Paper|Code|
|---|---|---|---|---|---|
|Luca Canalini|Registration of ultrasound volumes based on Euclidean distance transform|1.27|-|[arXiv](https://arxiv.org/abs/2001.03204)|[MeVisLab](https://www.mevislab.de/)|
|Wolfgang Wein|Brain-Shift Correction with Image-Based Registration and Landmark Accuracy Evaluation|1.75 (0.62)|1.57 (0.96)|[LNCS](https://link.springer.com/chapter/10.1007/978-3-030-01045-4_17)|-|
|Mattias P. Heinrich|Intra-operative Ultrasound to MRI Fusion with a Public Multimodal Discrete Registration Tool|1.67 (0.54)|1.87 (0.93)|[LNCS](https://link.springer.com/chapter/10.1007/978-3-030-01045-4_19)|[DeedsSSC](https://github.com/mattiaspaul/deedsBCV)|
|Inês Machado|Deformable MRI-Ultrasound Registration via Attribute Matching and Mutual-Saliency Weighting for Image-Guided Neurosurgery|3.35 (1.39) |2.18 (1.23)|[LNCS](https://link.springer.com/chapter/10.1007/978-3-030-01045-4_20)|[cDRAMMS](https://www.nitrc.org/projects/dramms/)|
|David Drobny|Registration of MRI and iUS Data to Compensate Brain Shift Using a Symmetric Block-Matching Based Approach|2.90 (3.59) |3.21 (3.57)|[LNCS](https://link.springer.com/chapter/10.1007/978-3-030-01045-4_21)|[NiftyReg](http://cmictig.cs.ucl.ac.uk/wiki/index.php/NiftyReg)|

> Values indicates the average (std) distances between larnmark pairs

> [MICCAI 2019 Winners](https://twitter.com/xiaobird/status/1184271136839950338)


### Register iUS after tumor resection to iUS before tumor resection

|First Author|Method|mTREs|Paper|Code|
|---|---|---|---|---|
|David Drobny|Landmark-Based Evaluation of a Block-Matching Registration Framework on the RESECT Pre- and Intra-operative Brain Image Data Set|1.92 (1.04)|[LNCS](https://link.springer.com/chapter/10.1007/978-3-030-33642-4_15)|[NiftyReg](https://github.com/KCL-BMEIS/niftyreg/wiki)|

>  mTREs: mean target registration errors 

