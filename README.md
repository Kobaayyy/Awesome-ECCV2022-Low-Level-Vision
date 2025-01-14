# Awesome-ECCV2022-Low-Level-Vision
A Collection of Papers and Codes in ECCV2022 related to Low-Level Vision

## Related collections for low-level vision
- [CVPR2022-Low-Level-Vision](https://github.com/DarrenPan/CVPR2022-Low-Level-Vision)
- [Awesome-AAAI2022-Low-Level-Vision](https://github.com/DarrenPan/Awesome-AAAI2022-Low-Level-Vision)
- [Awesome-NeurIPS2021-Low-Level-Vision](https://github.com/DarrenPan/Awesome-NeurIPS2021-Low-Level-Vision)
- [Awesome-ICCV2021-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-ICCV2021-Low-Level-Vision)
- [Awesome-CVPR2021/CVPR2020-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-CVPR2021-CVPR2020-Low-Level-Vision)
- [Awesome-ECCV2020-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-ECCV2020-Low-Level-Vision)


## Catalogue

- [Image Restoration](#ImageRetoration)
  - [Video Restoration](#VideoRestoration)
  
- [Super Resolution](#SuperResolution)
  - [Image Super Resolution](#ImageSuperResolution)
  - [Video Super Resolution](#VideoSuperResolution)
<!--
- [Image Rescaling](#Rescaling)

-->
- [Denoising](#Denoising)
  - [Image Denoising](#ImageDenoising)
  - [Video Denoising](#VideoDenoising)

- [Deblurring](#Deblurring)
  - [Image Deblurring](#ImageDeblurring)
  - [Video Deblurring](#VideoDeblurring)

- [Image Decomposition](#Decomposition)

- [Deraining](#Deraining)

- [Dehazing](#Dehazing)

- [Demoireing](#Demoireing)
<!--
- [Demosaicing](#Demosaicing)
-->
- [HDR Imaging / Multi-Exposure Image Fusion](#HDR)

- [Image Fusion](#Fusion)

- [Frame Interpolation](#FrameInterpolation)
  - [Spatial-Temporal Video Super-Resolution](#STVSR)
  
- [Image Enhancement](#Enhancement)
  - [Low-Light Image Enhancement](#LowLight)

- [Image Harmonization](#Harmonization)

- [Image Completion/Inpainting](#Inpainting)

- [Image Colorization](#Colorization)

- [Image Matting](#Matting)

- [Shadow Removal](#ShadowRemoval)

<!--
- [Image Stitching](#Stitching)
-->
- [Image Compression](#ImageCompression)

- [Image Quality Assessment](#ImageQualityAssessment)

- [Relighting](#Relighting)

- [Style Transfer](#StyleTransfer)

- [Image Editing](#ImageEditing)

- [Image Generation/Synthesis/ Image-to-Image Translation](#ImageGeneration)
  - [Video Generation](#VideoGeneration)


- [Others](#Others)


<a name="ImageRetoration"></a>
# Image Restoration - 图像恢复

**Simple Baselines for Image Restoration**
- Paper: https://arxiv.org/abs/2204.04676
- Code: https://github.com/megvii-research/NAFNet

**D2HNet: Joint Denoising and Deblurring with Hierarchical Network for Robust Night Image Restoration**
- Paper: https://arxiv.org/abs/2207.03294
- Code: https://github.com/zhaoyuzhi/D2HNet

**Seeing Far in the Dark with Patterned Flash**
- Paper: https://arxiv.org/abs/2207.12570
- Code: https://github.com/zhsun0357/Seeing-Far-in-the-Dark-with-Patterned-Flash

**BayesCap: Bayesian Identity Cap for Calibrated Uncertainty in Frozen Neural Networks**
- Paper: https://arxiv.org/abs/2207.06873
- Code: https://github.com/ExplainableML/BayesCap

**Improving Image Restoration by Revisiting Global Information Aggregation**
- Paper: https://arxiv.org/abs/2112.04491
- Code: https://github.com/megvii-research/TLC

**Fast Two-step Blind Optical Aberration Correction**
- Paper: https://arxiv.org/abs/2208.00950
- Code: https://github.com/teboli/fast_two_stage_psf_correction
- Tags: Optical Aberration Correction

**VQFR: Blind Face Restoration with Vector-Quantized Dictionary and Parallel Decoder**
- Paper: https://arxiv.org/abs/2205.06803
- Code: https://github.com/TencentARC/VQFR
- Tags: Blind Face Restoration

**RAWtoBit: A Fully End-to-end Camera ISP Network**
- Paper: https://arxiv.org/abs/2208.07639
- Tags: ISP and Image Compression

**Transform your Smartphone into a DSLR Camera: Learning the ISP in the Wild**
- Paper: https://arxiv.org/abs/2203.10636
- Code: https://github.com/4rdhendu/TransformPhone2DSLR
- Tags: ISP

**Single Frame Atmospheric Turbulence Mitigation: A Benchmark Study and A New Physics-Inspired Transformer Model**
- Paper: https://arxiv.org/abs/2207.10040
- Code: https://github.com/VITA-Group/TurbNet
- Tags: Atmospheric Turbulence Mitigation, Transformer

**Modeling Mask Uncertainty in Hyperspectral Image Reconstruction**
- Paper: https://arxiv.org/abs/2112.15362
- Code: https://github.com/Jiamian-Wang/mask_uncertainty_spectral_SCI
- Tags: Hyperspectral Image Reconstruction

**TAPE: Task-Agnostic Prior Embedding for Image Restoration**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3292_ECCV_2022_paper.php

**DRCNet: Dynamic Image Restoration Contrastive Network**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6389_ECCV_2022_paper.php

**ART-SS: An Adaptive Rejection Technique for Semi-Supervised Restoration for Adverse Weather-Affected Images**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4237_ECCV_2022_paper.php
- Code: https://github.com/rajeevyasarla/ART-SS
- Tags: Adverse Weather

**Spectrum-Aware and Transferable Architecture Search for Hyperspectral Image Restoration**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4367_ECCV_2022_paper.php
- Tags: Hyperspectral Image Restoration

**Seeing through a Black Box: Toward High-Quality Terahertz Imaging via Subspace-and-Attention Guided Restoration**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6259_ECCV_2022_paper.php
- Tags: Terahertz Imaging

**JPEG Artifacts Removal via Contrastive Representation Learning**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/171_ECCV_2022_paper.php
- Tags: JPEG Artifacts Removal

**Zero-Shot Learning for Reflection Removal of Single 360-Degree Image**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6418_ECCV_2022_paper.php
- Tags: Reflection Removal

**Overexposure Mask Fusion: Generalizable Reverse ISP Multi-Step Refinement**
- Paper: https://arxiv.org/abs/2210.11511
- Code: https://github.com/SenseBrainTech/overexposure-mask-reverse-ISP
- Tagss: [Workshop], Reversed ISP

<a name="VideoRestoration"></a>
## Video Restoration

**Video Restoration Framework and Its Meta-Adaptations to Data-Poor Conditions**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/7533_ECCV_2022_paper.php

<a name="SuperResolution"></a>
# Super Resolution - 超分辨率
<a name="ImageSuperResolution"></a>
## Image Super Resolution

**ARM: Any-Time Super-Resolution Method**
- Paper: https://arxiv.org/abs/2203.10812
- Code: https://github.com/chenbong/ARM-Net

**Dynamic Dual Trainable Bounds for Ultra-low Precision Super-Resolution Networks**
- Paper: https://arxiv.org/abs/2203.03844
- Code: https://github.com/zysxmu/DDTB

**CADyQ : Contents-Aware Dynamic Quantization for Image Super Resolution**
- Paper: https://arxiv.org/abs/2207.10345
- Code: https://github.com/Cheeun/CADyQ

**Image Super-Resolution with Deep Dictionary**
- Paper: https://arxiv.org/abs/2207.09228
- Code: https://github.com/shuntama/srdd

**Perception-Distortion Balanced ADMM Optimization for Single-Image Super-Resolution**
- Paper: https://arxiv.org/abs/2208.03324
- Code: https://github.com/Yuehan717/PDASR

**Adaptive Patch Exiting for Scalable Single Image Super-Resolution**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2021_ECCV_2022_paper.php
- Code: https://github.com/littlepure2333/APE

**Learning Series-Parallel Lookup Tables for Efficient Image Super-Resolution**
- Paper: https://arxiv.org/abs/2207.12987
- Code: https://github.com/zhjy2016/SPLUT
- Tags: Efficient

**MuLUT: Cooperating Mulitple Look-Up Tables for Efficient Image Super-Resolution**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136780234.pdf
- Code: https://github.com/ddlee-cn/MuLUT
- Tags: Efficient

**Efficient Long-Range Attention Network for Image Super-resolution**
- Paper: https://arxiv.org/abs/2203.06697
- Code: https://github.com/xindongzhang/ELAN

**Compiler-Aware Neural Architecture Search for On-Mobile Real-time Super-Resolution**
- Paper: https://arxiv.org/abs/2207.12577
- Code: https://github.com/wuyushuwys/compiler-aware-nas-sr

**Restore Globally, Refine Locally: A Mask-Guided Scheme to Accelerate Super-Resolution Networks**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4417_ECCV_2022_paper.php
- Code: https://github.com/huxiaotaostasy/MGA-scheme

**Learning Mutual Modulation for Self-Supervised Cross-Modal Super-Resolution**
- Paper: https://arxiv.org/abs/2207.09156
- Code: https://github.com/palmdong/MMSR
- Tags: Self-Supervised

**Self-Supervised Learning for Real-World Super-Resolution from Dual Zoomed Observations**
- Paper: https://arxiv.org/abs/2203.01325
- Code: https://github.com/cszhilu1998/SelfDZSR
- Tags: Self-Supervised, Reference-based

**Efficient and Degradation-Adaptive Network for Real-World Image Super-Resolution**
- Paper: http://www4.comp.polyu.edu.hk/~cslzhang/paper/ECCV2022_DASR.pdf
- Code: https://github.com/csjliang/DASR
- Tags: Real-World

**D2C-SR: A Divergence to Convergence Approach for Real-World Image Super-Resolution**
- Paper: https://arxiv.org/abs/2103.14373
- Code: https://github.com/megvii-research/D2C-SR
- Tag: Real-World

**MM-RealSR: Metric Learning based Interactive Modulation for Real-World Super-Resolution**
- Paper: https://arxiv.org/abs/2205.05065
- Code: https://github.com/TencentARC/MM-RealSR
- Tag: Real-World

**KXNet: A Model-Driven Deep Neural Network for Blind Super-Resolution**
- Paper: https://arxiv.org/abs/2209.10305
- Code: https://github.com/jiahong-fu/KXNet
- Tags: Blind

**From Face to Natural Image: Learning Real Degradation for Blind Image Super-Resolution**
- Paper: https://arxiv.org/abs/2210.00752
- Code: https://github.com/csxmli2016/ReDegNet
- Tags: Blind

**Unfolded Deep Kernel Estimation for Blind Image Super-Resolution**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3484_ECCV_2022_paper.php
- Code: https://github.com/natezhenghy/UDKE
- Tags: Blind

**Uncertainty Learning in Kernel Estimation for Multi-stage Blind Image Super-Resolution**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1649_ECCV_2022_paper.php
- Tags: Blind

**Super-Resolution by Predicting Offsets: An Ultra-Efficient Super-Resolution Network for Rasterized Images**
- Paper: https://arxiv.org/abs/2210.04198
- Code: https://github.com/HaomingCai/SRPO
- Tags: Rasterized Images

**Reference-based Image Super-Resolution with Deformable Attention Transformer**
- Paper: https://arxiv.org/abs/2207.11938
- Code: https://github.com/caojiezhang/DATSR
- Tags: Reference-based, Transformer

**RRSR:Reciprocal Reference-Based Image Super-Resolution with Progressive Feature Alignment and Selection**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/7808_ECCV_2022_paper.php
- Tags: Reference-based

**Boosting Event Stream Super-Resolution with a Recurrent Neural Network**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/248_ECCV_2022_paper.php
- Tags: Event

**HST: Hierarchical Swin Transformer for Compressed Image Super-resolution**
- Paper: https://arxiv.org/abs/2208.09885
- Tags: [Workshop-AIM2022]

**Swin2SR: SwinV2 Transformer for Compressed Image Super-Resolution and Restoration**
- Paper: https://arxiv.org/abs/2209.11345
- Code: https://github.com/mv-lab/swin2sr
- Tags: [Workshop-AIM2022]

**Fast Nearest Convolution for Real-Time Efficient Image Super-Resolution**
- Paper: https://arxiv.org/abs/2208.11609
- Code: https://github.com/Algolzw/NCNet
- Tags: [Workshop-AIM2022]

<a name="VideoSuperResolution"></a>
## Video Super Resolution

**Learning Spatiotemporal Frequency-Transformer for Compressed Video Super-Resolution**
- Paper: https://arxiv.org/abs/2208.03012
- Code: https://github.com/researchmm/FTVSR
- Tags: Compressed Video SR

**A Codec Information Assisted Framework for Efficient Compressed Video Super-Resolution**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6420_ECCV_2022_paper.php
- Tags: Compressed Video SR

**Real-RawVSR: Real-World Raw Video Super-Resolution with a Benchmark Dataset**
- Paper: https://arxiv.org/abs/2209.12475
- Code: https://github.com/zmzhang1998/Real-RawVSR


<a name="Denoising"></a>
# Denoising - 去噪

<a name="ImageDenoising"></a>
## Image Denoising

**Deep Semantic Statistics Matching (D2SM) Denoising Network**
- Paper: https://arxiv.org/abs/2207.09302
- Code: https://github.com/MKFMIKU/d2sm

**Fast and High Quality Image Denoising via Malleable Convolution**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3257_ECCV_2022_paper.php

<a name="VideoDenoising"></a>
## Video Denoising

**Unidirectional Video Denoising by Mimicking Backward Recurrent Modules with Look-ahead Forward Ones**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4024_ECCV_2022_paper.php
- Code: https://github.com/nagejacob/FloRNN

**TempFormer: Temporally Consistent Transformer for Video Denoising**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6092_ECCV_2022_paper.php
- Tags: Transformer

<a name="Deblurring"></a>
# Deblurring - 去模糊
<a name="ImageDeblurring"></a>
## Image Deblurring

**Learning Degradation Representations for Image Deblurring**
- Paper: https://arxiv.org/abs/2208.05244
- Code: https://github.com/dasongli1/Learning_degradation

**Stripformer: Strip Transformer for Fast Image Deblurring**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4651_ECCV_2022_paper.php
- Tags: Transformer

**Animation from Blur: Multi-modal Blur Decomposition with Motion Guidance**
- Paper: https://arxiv.org/abs/2207.10123
- Code: https://github.com/zzh-tech/Animation-from-Blur
- Tags: recovering detailed motion from a single motion-blurred image

**United Defocus Blur Detection and Deblurring via Adversarial Promoting Learning**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3308_ECCV_2022_paper.php
- Code: https://github.com/wdzhao123/APL
- Tags: Defocus Blur

**Realistic Blur Synthesis for Learning Image Deblurring**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6325_ECCV_2022_paper.php
- Tags: Blur Synthesis

**Event-based Fusion for Motion Deblurring with Cross-modal Attention**
- Paper:https://arxiv.org/abs/2112.00167
- Code: https://github.com/AHupuJR/EFNet
- Tags: Event-based

**Event-Guided Deblurring of Unknown Exposure Time Videos**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3601_ECCV_2022_paper.php
- Tags: Event-based

<a name="VideoDeblurring"></a>
## Video Deblurring

**Spatio-Temporal Deformable Attention Network for Video Deblurring**
- Paper: https://arxiv.org/abs/2207.10852
- Code: https://github.com/huicongzhang/STDAN

**Efficient Video Deblurring Guided by Motion Magnitude**
- Paper: https://arxiv.org/abs/2207.13374
- Code: https://github.com/sollynoay/MMP-RNN

**ERDN: Equivalent Receptive Field Deformable Network for Video Deblurring**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4085_ECCV_2022_paper.php
- Code: https://github.com/TencentCloud/ERDN

**DeMFI: Deep Joint Deblurring and Multi-Frame Interpolation with Flow-Guided Attentive Correlation and Recursive Boosting**
- Paper: https://arxiv.org/abs/2111.09985
- Code: https://github.com/JihyongOh/DeMFI
- Tags: Joint Deblurring and Frame Interpolation

**Towards Real-World Video Deblurring by Exploring Blur Formation Process**
- Paper: https://arxiv.org/abs/2208.13184
- Tags: [Workshop-AIM2022]

<a name="Decomposition"></a>
# Image Decomposition

**Blind Image Decomposition**
- Paper: https://arxiv.org/abs/2108.11364
- Code: https://github.com/JunlinHan/BID


<a name="Deraining"></a>
# Deraining - 去雨

**Not Just Streaks: Towards Ground Truth for Single Image Deraining**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1506_ECCV_2022_paper.php
- Code: https://github.com/UCLA-VMG/GT-RAIN

**Rethinking Video Rain Streak Removal: A New Synthesis Model and a Deraining Network with Video Rain Prior**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6798_ECCV_2022_paper.php
- Code: https://github.com/wangshauitj/RDD-Net


<a name="Dehazing"></a>
# Dehazing - 去雾

**Frequency and Spatial Dual Guidance for Image Dehazing**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4734_ECCV_2022_paper.php
- Code: https://github.com/yuhuUSTC/FSDGN 

**Perceiving and Modeling Density for Image Dehazing**
- Paper: https://arxiv.org/abs/2111.09733
- Code: https://github.com/Owen718/ECCV22-Perceiving-and-Modeling-Density-for-Image-Dehazing

**Boosting Supervised Dehazing Methods via Bi-Level Patch Reweighting**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1346_ECCV_2022_paper.php

**Unpaired Deep Image Dehazing Using Contrastive Disentanglement Learning**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/255_ECCV_2022_paper.php


<a name="Demoireing"></a>
# Demoireing - 去摩尔纹

**Towards Efficient and Scale-Robust Ultra-High-Definition Image Demoireing**
- Paper: https://arxiv.org/abs/2207.09935
- Code: https://github.com/XinYu-Andy/uhdm-page


 <a name="HDR"></a>
# HDR Imaging / Multi-Exposure Image Fusion - HDR图像生成 / 多曝光图像融合

**Exposure-Aware Dynamic Weighted Learning for Single-Shot HDR Imaging**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6250_ECCV_2022_paper.php
- Code: https://github.com/viengiaan/EDWL

**Ghost-free High Dynamic Range Imaging with Context-aware Transformer**
- Paper: https://arxiv.org/abs/2208.05114
- Code: https://github.com/megvii-research/HDR-Transformer

**Selective TransHDR: Transformer-Based Selective HDR Imaging Using Ghost Region Mask**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6670_ECCV_2022_paper.php

**HDR-Plenoxels: Self-Calibrating High Dynamic Range Radiance Fields**
- Paper: https://arxiv.org/abs/2208.06787
- Code: https://github.com/postech-ami/HDR-Plenoxels

**Towards Real-World HDRTV Reconstruction: A Data Synthesis-Based Approach**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4873_ECCV_2022_paper.php


<a name="Fusion"></a>
# Image Fusion

**FusionVAE: A Deep Hierarchical Variational Autoencoder for RGB Image Fusion**
- Paper: https://arxiv.org/abs/2209.11277

**Recurrent Correction Network for Fast and Efficient Multi-modality Image Fusion**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3864_ECCV_2022_paper.php
- Code: https://github.com/MisakiCoca/ReCoNet

**Neural Image Representations for Multi-Image Fusion and Layer Separation**
- Paper: https://arxiv.org/abs/2108.01199
- Code: https://shnnam.github.io/research/nir/

**Fusion from Decomposition: A Self-Supervised Decomposition Approach for Image Fusion**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4260_ECCV_2022_paper.php
- Code: https://github.com/erfect2020/DecompositionForFusion


<a name="FrameInterpolation"></a>
# Frame Interpolation - 插帧

**Real-Time Intermediate Flow Estimation for Video Frame Interpolation**
- Paper: https://arxiv.org/abs/2011.06294
- Code: https://github.com/hzwer/ECCV2022-RIFE 

**FILM: Frame Interpolation for Large Motion**
- Paper: https://arxiv.org/abs/2202.04901
- Code: https://github.com/google-research/frame-interpolation

**Video Interpolation by Event-driven Anisotropic Adjustment of Optical Flow**
- Paper: https://arxiv.org/abs/2208.09127

**Learning Cross-Video Neural Representations for High-Quality Frame Interpolation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2565_ECCV_2022_paper.php

**Deep Bayesian Video Frame Interpolation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1287_ECCV_2022_paper.php
- Code: https://github.com/Oceanlib/DBVI

**A Perceptual Quality Metric for Video Frame Interpolation**
- Paper: https://arxiv.org/abs/2210.01879
- Code: https://github.com/hqqxyy/VFIPS

**DeMFI: Deep Joint Deblurring and Multi-Frame Interpolation with Flow-Guided Attentive Correlation and Recursive Boosting**
- Paper: https://arxiv.org/abs/2111.09985
- Code: https://github.com/JihyongOh/DeMFI
- Tags: Joint Deblurring and Frame Interpolation

<a name="STVSR"></a>
## Spatial-Temporal Video Super-Resolution

**Towards Interpretable Video Super-Resolution via Alternating Optimization**
- Paper: https://arxiv.org/abs/2207.10765
- Code: https://github.com/caojiezhang/DAVSR


<a name="Enhancement"></a>
# Image Enhancement - 图像增强

**Local Color Distributions Prior for Image Enhancement**
- Paper: https://www.cs.cityu.edu.hk/~rynson/papers/eccv22b.pdf
- Code: https://github.com/hywang99/LCDPNet

**SepLUT: Separable Image-adaptive Lookup Tables for Real-time Image Enhancement**
- Paper: https://arxiv.org/abs/2207.08351

**Neural Color Operators for Sequential Image Retouching**
- Paper: https://arxiv.org/abs/2207.08080
- Code: https://github.com/amberwangyili/neurop

**Deep Fourier-Based Exposure Correction Network with Spatial-Frequency Interaction**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4678_ECCV_2022_paper.php
- Tags: Exposure Correction

**Uncertainty Inspired Underwater Image Enhancement**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3298_ECCV_2022_paper.php
- Tags: Underwater Image Enhancement

**NEST: Neural Event Stack for Event-Based Image Enhancement**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2730_ECCV_2022_paper.php
- Tags: Event-Based

<a name="LowLight"></a>
## Low-Light Image Enhancement

**LEDNet: Joint Low-light Enhancement and Deblurring in the Dark**
- Paper: https://arxiv.org/abs/2202.03373
- Code: https://github.com/sczhou/LEDNet

**Unsupervised Night Image Enhancement: When Layer Decomposition Meets Light-Effects Suppression**
- Paper: https://arxiv.org/abs/2207.10564
- Code: https://github.com/jinyeying/night-enhancement

<a name="Harmonization"></a>
# Image Harmonization - 图像协调

**Harmonizer: Learning to Perform White-Box Image and Video Harmonization**
- Paper: https://arxiv.org/abs/2207.01322
- Code: https://github.com/ZHKKKe/Harmonizer

**DCCF: Deep Comprehensible Color Filter Learning Framework for High-Resolution Image Harmonization**
- Paper: https://arxiv.org/abs/2207.04788
- Code: https://github.com/rockeyben/DCCF

**Semantic-Guided Multi-Mask Image Harmonization**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3151_ECCV_2022_paper.php
- Code: https://github.com/XuqianRen/Semantic-guided-Multi-mask-Image-Harmonization

**Spatial-Separated Curve Rendering Network for Efficient and High-Resolution Image Harmonization**
- Paper: https://arxiv.org/abs/2109.05750
- Code: https://github.com/stefanLeong/S2CRNet

<a name="Inpainting"></a>
# Image Completion/Inpainting - 图像修复

**Learning Prior Feature and Attention Enhanced Image Inpainting**
- Paper: https://arxiv.org/abs/2208.01837
- Code: https://github.com/ewrfcas/MAE-FAR

**Perceptual Artifacts Localization for Inpainting**
- Paper: https://arxiv.org/abs/2208.03357
- Code: https://github.com/owenzlz/PAL4Inpaint

**High-Fidelity Image Inpainting with GAN Inversion**
- Paper: https://arxiv.org/abs/2208.11850

**Unbiased Multi-Modality Guidance for Image Inpainting**
- Paper: https://arxiv.org/abs/2208.11844

**Image Inpainting with Cascaded Modulation GAN and Object-Aware Training**
- Paper: https://arxiv.org/abs/2203.11947
- Code: https://github.com/htzheng/CM-GAN-Inpainting

**Inpainting at Modern Camera Resolution by Guided PatchMatch with Auto-Curation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5789_ECCV_2022_paper.php

**Diverse Image Inpainting with Normalizing Flow**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2814_ECCV_2022_paper.php

**Hourglass Attention Network for Image Inpainting**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3369_ECCV_2022_paper.php

**Perceptual Artifacts Localization for Inpainting**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2153_ECCV_2022_paper.php

**Don't Forget Me: Accurate Background Recovery for Text Removal via Modeling Local-Global Context**
- Paper: https://arxiv.org/abs/2207.10273
- Code: https://github.com/lcy0604/CTRNet
- Tags: Text Removal

**The Surprisingly Straightforward Scene Text Removal Method with Gated Attention and Region of Interest Generation: A Comprehensive Prominent Model Analysis**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4705_ECCV_2022_paper.php
- Code: https://github.com/naver/garnet
- Tags: Text Removal

## Video Inpainting

**Error Compensation Framework for Flow-Guided Video Inpainting**
- Paper: https://arxiv.org/abs/2207.10391

**Flow-Guided Transformer for Video Inpainting**
- Paper: https://arxiv.org/abs/2208.06768
- Code: https://github.com/hitachinsk/FGT


<a name="Colorization"></a>
# Image Colorization - 图像上色

**Eliminating Gradient Conflict in Reference-based Line-art Colorization**
- Paper: https://arxiv.org/abs/2207.06095
- Code: https://github.com/kunkun0w0/SGA

**Bridging the Domain Gap towards Generalization in Automatic Colorization**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/7304_ECCV_2022_paper.php
- Code: https://github.com/Lhyejin/DG-Colorization

**CT2: Colorization Transformer via Color Tokens**
- Paper: https://ci.idm.pku.edu.cn/Weng_ECCV22b.pdf
- Code: https://github.com/shuchenweng/CT2

**PalGAN: Image Colorization with Palette Generative Adversarial Networks**
- Paper: https://arxiv.org/abs/2210.11204
- Code: https://github.com/shepnerd/PalGAN

**BigColor: Colorization using a Generative Color Prior for Natural Images**
- Paper: https://kimgeonung.github.io/assets/bigcolor/bigcolor_main.pdf
- Code: https://github.com/KIMGEONUNG/BigColor

**Semantic-Sparse Colorization Network for Deep Exemplar-Based Colorization**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/820_ECCV_2022_paper.php

**ColorFormer: Image Colorization via Color Memory Assisted Hybrid-Attention Transformer**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3385_ECCV_2022_paper.php

**L-CoDer: Language-Based Colorization with Color-Object Decoupling Transformer**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2424_ECCV_2022_paper.php

**Colorization for In Situ Marine Plankton Images**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6905_ECCV_2022_paper.php


<a name="Matting"></a>
# Image Matting - 图像抠图

**TransMatting: Enhancing Transparent Objects Matting with Transformers**
- Paper: https://arxiv.org/abs/2208.03007
- Code: https://github.com/AceCHQ/TransMatting

**One-Trimap Video Matting**
- Paper: https://arxiv.org/abs/2207.13353
- Code: https://github.com/Hongje/OTVM


<a name="ShadowRemoval"></a>
# Shadow Removal - 阴影消除

**Style-Guided Shadow Removal**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5580_ECCV_2022_paper.php
- Code: https://github.com/jinwan1994/SG-ShadowNet


<a name="ImageCompression"></a>
# Image Compression - 图像压缩

**Optimizing Image Compression via Joint Learning with Denoising**
- Paper: https://arxiv.org/abs/2207.10869
- Code: https://github.com/felixcheng97/DenoiseCompression

**Implicit Neural Representations for Image Compression**
- Paper: https://arxiv.org/abs/2112.04267
- Code：https://github.com/YannickStruempler/inr_based_compression

**Expanded Adaptive Scaling Normalization for End to End Image Compression**
- Paper: https://arxiv.org/abs/2208.03049

**Content-Oriented Learned Image Compression**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/7542_ECCV_2022_paper.php
- Code: https://github.com/lmijydyb/COLIC

**Contextformer: A Transformer with Spatio-Channel Attention for Context Modeling in Learned Image Compression**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6046_ECCV_2022_paper.php

**Content Adaptive Latents and Decoder for Neural Image Compression**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4016_ECCV_2022_paper.php

## Video Compression

**AlphaVC: High-Performance and Efficient Learned Video Compression**
- Paper: https://arxiv.org/abs/2207.14678

**CANF-VC: Conditional Augmented Normalizing Flows for Video Compression**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3904_ECCV_2022_paper.php
- Code: https://github.com/NYCU-MAPL/CANF-VC

**Neural Video Compression Using GANs for Detail Synthesis and Propagation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4802_ECCV_2022_paper.php


<a name="ImageQualityAssessment"></a>
# Image Quality Assessment - 图像质量评价

**FAST-VQA: Efficient End-to-end Video Quality Assessment with Fragment Sampling**
- Paper: https://arxiv.org/abs/2207.02595
- Code: https://github.com/TimothyHTimothy/FAST-VQA

**Shift-tolerant Perceptual Similarity Metric**
- Paper: https://arxiv.org/abs/2207.13686
- Code: https://github.com/abhijay9/ShiftTolerant-LPIPS/

**Telepresence Video Quality Assessment**
- Paper: https://arxiv.org/abs/2207.09956

**A Perceptual Quality Metric for Video Frame Interpolation**
- Paper: https://arxiv.org/abs/2210.01879
- Code: https://github.com/hqqxyy/VFIPS


<a name="Relighting"></a>
# Relighting/Delighting

**Deep Portrait Delighting**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4581_ECCV_2022_paper.php

**Geometry-Aware Single-Image Full-Body Human Relighting**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4385_ECCV_2022_paper.php

**NeRF for Outdoor Scene Relighting**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4998_ECCV_2022_paper.php

**Physically-Based Editing of Indoor Scene Lighting from a Single Image**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1276_ECCV_2022_paper.php


<a name="StyleTransfer"></a>
# Style Transfer - 风格迁移

**CCPL: Contrastive Coherence Preserving Loss for Versatile Style Transfer**
- Paper: https://arxiv.org/abs/2207.04808
- Code: https://github.com/JarrentWu1031/CCPL

**Image-Based CLIP-Guided Essence Transfer**
- Paper: https://arxiv.org/abs/2110.12427 
- Code: https://github.com/hila-chefer/TargetCLIP

**Learning Graph Neural Networks for Image Style Transfer**
- Paper: https://arxiv.org/abs/2207.11681

**WISE: Whitebox Image Stylization by Example-based Learning**
- Paper: https://arxiv.org/abs/2207.14606
- Code: https://github.com/winfried-loetzsch/wise

**Language-Driven Artistic Style Transfer**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6627_ECCV_2022_paper.php

**MoDA: Map Style Transfer for Self-Supervised Domain Adaptation of Embodied Agents**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1762_ECCV_2022_paper.php

**JoJoGAN: One Shot Face Stylization**
- Paper: https://arxiv.org/abs/2112.11641
- Code: https://github.com/mchong6/JoJoGAN

**EleGANt: Exquisite and Locally Editable GAN for Makeup Transfer**
- Paper: https://arxiv.org/abs/2207.09840
- Code: https://github.com/Chenyu-Yang-2000/EleGANt
- Tags: Makeup Transfer

**RamGAN: Region Attentive Morphing GAN for Region-Level Makeup Transfer**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/803_ECCV_2022_paper.php
- Tags: Makeup Transfer

<a name="ImageEditing"></a>
# Image Editing - 图像编辑

**Context-Consistent Semantic Image Editing with Style-Preserved Modulation**
- Paper: https://arxiv.org/abs/2207.06252
- Code: https://github.com/WuyangLuo/SPMPGAN

**GAN with Multivariate Disentangling for Controllable Hair Editing**
- Paper: https://raw.githubusercontent.com/XuyangGuo/xuyangguo.github.io/main/database/CtrlHair/CtrlHair.pdf
- Code: https://github.com/XuyangGuo/CtrlHair

**Paint2Pix: Interactive Painting based Progressive Image Synthesis and Editing**
- Paper: https://arxiv.org/abs/2208.08092
- Code: https://github.com/1jsingh/paint2pix

**High-fidelity GAN Inversion with Padding Space**
- Paper: https://arxiv.org/abs/2203.11105
- Code: https://github.com/EzioBy/padinv

**Text2LIVE: Text-Driven Layered Image and Video Editing**
- Paper: https://arxiv.org/abs/2204.02491
- Code: https://github.com/omerbt/Text2LIVE

**IntereStyle: Encoding an Interest Region for Robust StyleGAN Inversion**
- Paper: https://arxiv.org/abs/2209.10811

**Style Your Hair: Latent Optimization for Pose-Invariant Hairstyle Transfer via Local-Style-Aware Hair Alignment**
- Paper: https://arxiv.org/abs/2208.07765
- Code: https://github.com/Taeu/Style-Your-Hair

**HairNet: Hairstyle Transfer with Pose Changes**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5227_ECCV_2022_paper.php

**End-to-End Visual Editing with a Generatively Pre-trained Artist**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/841_ECCV_2022_paper.php

**The Anatomy of Video Editing: A Dataset and Benchmark Suite for AI-Assisted Video Editing**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4736_ECCV_2022_paper.php

**Scraping Textures from Natural Images for Synthesis and Editing**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2180_ECCV_2022_paper.php

**VQGAN-CLIP: Open Domain Image Generation and Editing with Natural Language Guidance**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/8048_ECCV_2022_paper.php

**Editing Out-of-Domain GAN Inversion via Differential Activations**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5504_ECCV_2022_paper.php
- Code: https://github.com/HaoruiSong622/Editing-Out-of-Domain

**ChunkyGAN: Real Image Inversion via Segments**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5092_ECCV_2022_paper.php

**FairStyle: Debiasing StyleGAN2 with Style Channel Manipulations**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/7746_ECCV_2022_paper.php
- Code: https://github.com/catlab-team/fairstyle

**A Style-Based GAN Encoder for High Fidelity Reconstruction of Images and Videos**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2740_ECCV_2022_paper.php
- Code: https://github.com/InterDigitalInc/FeatureStyleEncoder

**Rayleigh EigenDirections (REDs): Nonlinear GAN latent space traversals for multidimensional features**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/7277_ECCV_2022_paper.php

<a name=ImageGeneration></a>
# Image Generation/Synthesis / Image-to-Image Translation - 图像生成/合成/转换

## Text-to-Image / Text Guided / Multi-Modal

**TIPS: Text-Induced Pose Synthesis**
- Paper: https://arxiv.org/abs/2207.11718
- Code: https://github.com/prasunroy/tips

**TISE: A Toolbox for Text-to-Image Synthesis Evaluation**
- Paper: https://arxiv.org/abs/2112.01398
- Code: https://github.com/VinAIResearch/tise-toolbox

**Learning Visual Styles from Audio-Visual Associations**
- Paper: https://arxiv.org/abs/2205.05072
- Code: https://github.com/Tinglok/avstyle

**Multimodal Conditional Image Synthesis with Product-of-Experts GANs**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3539_ECCV_2022_paper.php
- Project: https://deepimagination.cc/PoE-GAN/

**NÜWA: Visual Synthesis Pre-training for Neural visUal World creAtion**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5422_ECCV_2022_paper.php

**Make-a-Scene: Scene-Based Text-to-Image Generation with Human Priors**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/993_ECCV_2022_paper.php

**Trace Controlled Text to Image Generation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1894_ECCV_2022_paper.php

**Audio-Driven Stylized Gesture Generation with Flow-Based Model**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3948_ECCV_2022_paper.php

**No Token Left Behind: Explainability-Aided Image Classification and Generation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2764_ECCV_2022_paper.php

## Image-to-Image / Image Guided

**End-to-end Graph-constrained Vectorized Floorplan Generation with Panoptic Refinement**
- Paper: https://arxiv.org/abs/2207.13268

**ManiFest: Manifold Deformation for Few-shot Image Translation**
- Paper: https://arxiv.org/abs/2111.13681
- Code: https://github.com/cv-rits/ManiFest

**VecGAN: Image-to-Image Translation with Interpretable Latent Directions**
- Paper: https://arxiv.org/abs/2207.03411

**DynaST: Dynamic Sparse Transformer for Exemplar-Guided Image Generation**
- Paper: https://arxiv.org/abs/2207.06124
- Code: https://github.com/Huage001/DynaST

**Cross Attention Based Style Distribution for Controllable Person Image Synthesis**
- Paper: https://arxiv.org/abs/2208.00712
- Code: https://github.com/xyzhouo/CASD

**Vector Quantized Image-to-Image Translation**
- Paper: https://arxiv.org/abs/2207.13286
- Code: https://github.com/cyj407/VQ-I2I

**URUST: Ultra-high-resolution unpaired stain transformation via Kernelized Instance Normalization**
- Paper: https://arxiv.org/abs/2208.10730
- Code: https://github.com/Kaminyou/URUST

**General Object Pose Transformation Network from Unpaired Data**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5972_ECCV_2022_paper.php
- Code: https://github.com/suyukun666/UFO-PT

**Unpaired Image Translation via Vector Symbolic Architectures**
- Paper: https://arxiv.org/abs/2209.02686
- Code: https://github.com/facebookresearch/vsait

**Supervised Attribute Information Removal and Reconstruction for Image Manipulation**
- Paper: https://arxiv.org/abs/2207.06555
- Code: https://github.com/NannanLi999/AIRR

**Bi-Level Feature Alignment for Versatile Image Translation and Manipulation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3912_ECCV_2022_paper.php

**Multi-Curve Translator for High-Resolution Photorealistic Image Translation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1278_ECCV_2022_paper.php

**CoGS: Controllable Generation and Search from Sketch and Style**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5160_ECCV_2022_paper.php

**AgeTransGAN for Facial Age Transformation with Rectified Performance Metrics**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1344_ECCV_2022_paper.php
- Code: https://github.com/AvLab-CV/AgeTransGAN

## Others for image generation

**StyleLight: HDR Panorama Generation for Lighting Estimation and Editing**
- Paper: https://arxiv.org/abs/2207.14811
- Code: https://github.com/Wanggcong/StyleLight

**Accelerating Score-based Generative Models with Preconditioned Diffusion Sampling**
- Paper: https://arxiv.org/abs/2207.02196
- Code: https://github.com/fudan-zvg/PDS

**GAN Cocktail: mixing GANs without dataset access**
- Paper: https://arxiv.org/abs/2106.03847
- Code: https://github.com/omriav/GAN-cocktail

**Compositional Visual Generation with Composable Diffusion Models**
- Paper: https://arxiv.org/abs/2206.01714
- Code: https://github.com/energy-based-model/Compositional-Visual-Generation-with-Composable-Diffusion-Models-PyTorch

**Adaptive-Feature-Interpolation-for-Low-Shot-Image-Generation**
- Paper: https://arxiv.org/abs/2112.02450
- Code: https://github.com/dzld00/Adaptive-Feature-Interpolation-for-Low-Shot-Image-Generation

**StyleHEAT: One-Shot High-Resolution Editable Talking Face Generation via Pretrained StyleGAN**
- Paper: https://arxiv.org/abs/2203.04036
- Code: https://github.com/FeiiYin/StyleHEAT

**WaveGAN: An Frequency-aware GAN for High-Fidelity Few-shot Image Generation**
- Paper: https://arxiv.org/abs/2207.07288
- Code: https://github.com/kobeshegu/ECCV2022_WaveGAN

**FakeCLR: Exploring Contrastive Learning for Solving Latent Discontinuity in Data-Efficient GANs**
- Paper: https://arxiv.org/abs/2207.08630
- Code: https://github.com/iceli1007/FakeCLR

**Auto-regressive Image Synthesis with Integrated Quantization**
- Paper: https://arxiv.org/abs/2207.10776
- Code: https://github.com/fnzhan/IQ-VAE

**PixelFolder: An Efficient Progressive Pixel Synthesis Network for Image Generation**
- Paper: https://arxiv.org/abs/2204.00833
- Code: https://github.com/BlingHe/PixelFolder

**DeltaGAN: Towards Diverse Few-shot Image Generation with Sample-Specific Delta**
- Paper: https://arxiv.org/abs/2207.10271
- Code: https://github.com/bcmi/DeltaGAN-Few-Shot-Image-Generation

**Generator Knows What Discriminator Should Learn in Unconditional GANs**
- Paper: https://arxiv.org/abs/2207.13320
- Code: https://github.com/naver-ai/GGDR

**Hierarchical Semantic Regularization of Latent Spaces in StyleGANs**
- Paper: https://arxiv.org/abs/2208.03764
- Code: https://drive.google.com/file/d/1gzHTYTgGBUlDWyN_Z3ORofisQrHChg_n/view

**FurryGAN: High Quality Foreground-aware Image Synthesis**
- Paper: https://arxiv.org/abs/2208.10422
- Project: https://jeongminb.github.io/FurryGAN/

**Improving GANs for Long-Tailed Data through Group Spectral Regularization**
- Paper: https://arxiv.org/abs/2208.09932
- Code: https://drive.google.com/file/d/1aG48i04Q8mOmD968PAgwEvPsw1zcS4Gk/view

**Exploring Gradient-based Multi-directional Controls in GANs**
- Paper: https://arxiv.org/abs/2209.00698
- Code: https://github.com/zikuncshelly/GradCtrl

**Improved Masked Image Generation with Token-Critic**
- Paper: https://arxiv.org/abs/2209.04439

**Weakly-Supervised Stitching Network for Real-World Panoramic Image Generation**
- Paper: https://arxiv.org/abs/2209.05968
- Project: https://eadcat.github.io/WSSN

**Any-Resolution Training for High-Resolution Image Synthesis**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3693_ECCV_2022_paper.php
- Code: https://github.com/chail/anyres-gan

**BIPS: Bi-modal Indoor Panorama Synthesis via Residual Depth-Aided Adversarial Learning**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4327_ECCV_2022_paper.php
- Code: https://github.com/chang9711/BIPS

**Few-Shot Image Generation with Mixup-Based Distance Learning**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2709_ECCV_2022_paper.php
- Code: https://github.com/reyllama/mixdl

**StyleGAN-Human: A Data-Centric Odyssey of Human Generation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3366_ECCV_2022_paper.php
- Code: https://github.com/stylegan-human/StyleGAN-Human

**StyleFace: Towards Identity-Disentangled Face Generation on Megapixels**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4255_ECCV_2022_paper.php

**Contrastive Learning for Diverse Disentangled Foreground Generation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4323_ECCV_2022_paper.php

**BLT: Bidirectional Layout Transformer for Controllable Layout Generation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/7035_ECCV_2022_paper.php
- Code: https://github.com/google-research/google-research/tree/master/layout-blt

**Entropy-Driven Sampling and Training Scheme for Conditional Diffusion Generation**
- Paper: https://arxiv.org/abs/2206.11474
- Code: https://github.com/ZGCTroy/ED-DPM

**Unleashing Transformers: Parallel Token Prediction with Discrete Absorbing Diffusion for Fast High-Resolution Image Generation from Vector-Quantized Codes**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5081_ECCV_2022_paper.php

**DuelGAN: A Duel between Two Discriminators Stabilizes the GAN Training**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/7143_ECCV_2022_paper.php
- Code: https://github.com/UCSC-REAL/DuelGAN

<a name="VideoGeneration"></a>
## Video Generation

**Long Video Generation with Time-Agnostic VQGAN and Time-Sensitive Transformer**
- Paper: https://arxiv.org/abs/2204.03638
- Code: https://github.com/SongweiGe/TATS

**Controllable Video Generation through Global and Local Motion Dynamics**
- Paper: https://arxiv.org/abs/2204.06558
- Code: https://github.com/Araachie/glass

**Fast-Vid2Vid: Spatial-Temporal Compression for Video-to-Video Synthesis**
- Paper: https://arxiv.org/abs/2207.05049
- Code: https://github.com/fast-vid2vid/fast-vid2vid

**Synthesizing Light Field Video from Monocular Video**
- Paper: https://arxiv.org/abs/2207.10357
- Code: https://github.com/ShrisudhanG/Synthesizing-Light-Field-Video-from-Monocular-Video

**StoryDALL-E: Adapting Pretrained Text-to-Image Transformers for Story Continuation**
- Paper: https://arxiv.org/abs/2209.06192
- Code: https://github.com/adymaharana/storydalle

**Motion Transformer for Unsupervised Image Animation**
- Paper: 
- Code: https://github.com/JialeTao/MoTrans

**Sound-Guided Semantic Video Generation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5584_ECCV_2022_paper.php
- Code: https://github.com/anonymous5584/sound-guided-semantic-video-generation

**Layered Controllable Video Generation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4847_ECCV_2022_paper.php

**Diverse Generation from a Single Video Made Possible**
- Paper: https://arxiv.org/abs/2109.08591
- Code: https://github.com/nivha/single_video_generation

**Semantic-Aware Implicit Neural Audio-Driven Video Portrait Generation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/631_ECCV_2022_paper.php
- Code: https://github.com/alvinliu0/SSP-NeRF

**EAGAN: Efficient Two-Stage Evolutionary Architecture Search for GANs**
 - Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3419_ECCV_2022_paper.php
 - Code: https://github.com/marsggbo/EAGAN

**BlobGAN: Spatially Disentangled Scene Representations**
- Paper: https://arxiv.org/abs/2205.02837 
- Code: https://github.com/dave-epstein/blobgan

<a name="Others"></a>
# Others

**Learning Local Implicit Fourier Representation for Image Warping**
- Paper: https://ipl.dgist.ac.kr/LTEW.pdf
- Code: https://github.com/jaewon-lee-b/ltew
- Tags: Image Warping

**Dress Code: High-Resolution Multi-Category Virtual Try-On**
- Paper: https://arxiv.org/abs/2204.08532
- Code: https://github.com/aimagelab/dress-code
- Tags: Virtual Try-On

**High-Resolution Virtual Try-On with Misalignment and Occlusion-Handled Conditions**
- Paper: https://arxiv.org/abs/2206.14180
- Code: https://github.com/sangyun884/HR-VITON
- Tags: Virtual Try-On

**Single Stage Virtual Try-on via Deformable Attention Flows**
- Paper: https://arxiv.org/abs/2207.09161
- Tags: Virtual Try-On

**Outpainting by Queries**
- Paper: https://arxiv.org/abs/2207.05312
- Code: https://github.com/Kaiseem/QueryOTR
- Tags: Outpainting

**Watermark Vaccine: Adversarial Attacks to Prevent Watermark Removal**
- Paper: https://arxiv.org/abs/2207.08178
- Code: https://github.com/thinwayliu/Watermark-Vaccine
- Tags: Watermark Protection

**Efficient Meta-Tuning for Content-aware Neural Video Delivery**
- Paper: https://arxiv.org/abs/2207.09691
- Code: https://github.com/Neural-video-delivery/EMT-Pytorch-ECCV2022
- Tags: Video Delivery

**Human-centric Image Cropping with Partition-aware and Content-preserving Features**
- Paper: https://arxiv.org/abs/2207.10269
- Code: https://github.com/bcmi/Human-Centric-Image-Cropping

**CelebV-HQ: A Large-Scale Video Facial Attributes Dataset**
- Paper: https://arxiv.org/abs/2207.12393
- Code: https://github.com/CelebV-HQ/CelebV-HQ
- Tags: Dataset

**Learning Dynamic Facial Radiance Fields for Few-Shot Talking Head Synthesis**
- Paper: https://arxiv.org/abs/2207.11770
- Code: https://github.com/sstzal/DFRF
- Tags: Talking Head Synthesis

**Responsive Listening Head Generation: A Benchmark Dataset and Baseline**
- Paper: https://arxiv.org/abs/2112.13548 
- Code: https://github.com/dc3ea9f/vico_challenge_baseline

**Contrastive Monotonic Pixel-Level Modulation**
- Paper: https://arxiv.org/abs/2207.11517
- Code: https://github.com/lukun199/MonoPix

**AutoTransition: Learning to Recommend Video Transition Effects**
- Paper: https://arxiv.org/abs/2207.13479
- Code: https://github.com/acherstyx/AutoTransition

**Bringing Rolling Shutter Images Alive with Dual Reversed Distortion**
- Paper: https://arxiv.org/abs/2203.06451
- Code: https://github.com/zzh-tech/Dual-Reversed-RS

**Learning Object Placement via Dual-path Graph Completion**
- Paper: https://arxiv.org/abs/2207.11464
- Code: https://github.com/bcmi/GracoNet-Object-Placement

**DeepMCBM: A Deep Moving-camera Background Model**
- Paper: https://arxiv.org/abs/2209.07923
- Code: https://github.com/BGU-CS-VIL/DeepMCBM

**Mind the Gap in Distilling StyleGANs**
- Paper: https://arxiv.org/abs/2208.08840
- Code: https://github.com/xuguodong03/StyleKD

**StyleSwap: Style-Based Generator Empowers Robust Face Swapping**
- Paper: https://arxiv.org/abs/2209.13514
- Code: https://github.com/Seanseattle/StyleSwap
- Tags: Face Swapping

**Geometric Representation Learning for Document Image Rectification**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/1698_ECCV_2022_paper.php
- Code: https://github.com/fh2019ustc/DocGeoNet
- Tags: Document Image Rectification

**Studying Bias in GANs through the Lens of Race**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2581_ECCV_2022_paper.php
- Tags: Racial Bias

**On the Robustness of Quality Measures for GANs**
- Paper: https://arxiv.org/abs/2201.13019
- Code: https://github.com/MotasemAlfarra/R-FID-Robustness-of-Quality-Measures-for-GANs

**TREND: Truncated Generalized Normal Density Estimation of Inception Embeddings for GAN Evaluation**
- Paper: https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3604_ECCV_2022_paper.php
- Tags: GAN Evaluation

<!--
****
- Paper: 
- Code: 
-->
