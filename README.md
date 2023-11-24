<p align="center">
  <h3 align="center">Awesome-Single-Image-Reflection-Removal(SIRR)
  </h3>
  <p align="center">A collection of Single image reflection removal.  
    <br />
    <br />
    <br />
    <a href="https://github.com/TaoWangzj/Awesome-Face-Restoration/issues/new">Suggest new item</a>
    <br />
    <a href="https://github.com/TaoWangzj/Awesome-Face-Restoration/issues/new">Report Bug</a>
  </p>
</p>

This repository provides a summary of deep learning-based SIRR algorithms. All of these methods have been verified through the [DBLP](https://dblp.org/). 

## To-Do-List

- [ ]  SIRR methods classification

## Table of contents

- [SIRR](#sirr)
- [Image Quality Assessment](#image-quality-assessment)
- [Benchmark Datasets](#benchmark-datasets)

## SIRR

| Year | Pub | Title | Links |
| --- | --- | --- | --- |
| 2014 | CVPR | Single image layer separation using relative smoothness | \[[paper](https://yu-li.github.io/paper/li_cvpr14_layer.pdf)\]<br />\[[code](https://github.com/alexch1/ImageProcessing)\] |
| 2017 | ICCV | Benchmarking Single-Image Reflection Removal Algorithms | \[[paper](https://openaccess.thecvf.com/content_ICCV_2017/papers/Wan_Benchmarking_Single-Image_Reflection_ICCV_2017_paper.pdf)\]<br />\[[website](https://sir2data.github.io/)\] |
| 2017 | ICCV | A Generic Deep Architecture for Single Image Reflection Removal and Image Smoothing | \[[paper](https://openaccess.thecvf.com/content_ICCV_2017/papers/Fan_A_Generic_Deep_ICCV_2017_paper.pdf)\]<br />\[[code](https://github.com/fqnchina/CEILNet)\] |
| 2018 | ECCV | Seeing deeply and bidirectionally: A deep learning approach for single image reflection removal | \[[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Jie_Yang_Seeing_Deeply_and_ECCV_2018_paper.pdf)\]<br />\[[code](https://github.com/yangj1e/bdn-refremv)\] |
| 2018 | CVPR | Single image reflection separation with perceptual losses | \[[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Single_Image_Reflection_CVPR_2018_paper.pdf)\]<br />\[[code](https://github.com/ceciliavision/perceptual-reflection-removal)\] |
| 2018 | CVPR | CRRN: Multi-Scale Guided Concurrent Reflection Removal Network | \[[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Wan_CRRN_Multi-Scale_Guided_CVPR_2018_paper.pdf)\]<br />\[[code](https://github.com/He-jerry/CRRN)\](not official) |
| 2019 | CVPR | Single image reflection removal exploiting misaligned training data and network enhancements | \[[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wei_Single_Image_Reflection_Removal_Exploiting_Misaligned_Training_Data_and_Network_CVPR_2019_paper.pdf)\]<br />\[[code](https://github.com/Vandermode/ERRNet)\] |
| 2019 | CVPR | Single Image Reflection Removal Beyond Linearity | \[[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wen_Single_Image_Reflection_Removal_Beyond_Linearity_CVPR_2019_paper.pdf)\]<br />\[[code](https://github.com/csqiangwen/Single-Image-Reflection-Removal-Beyond-Linearity)\] |
| 2019 | PAMI | CoRRN: Cooperative Reflection Removal Network | \[[paper](https://camera.pku.edu.cn/TPAMI19c.pdf)\]<br />\[[code](https://github.com/wanrenjie/CoRRN)\] |
| 2020 | CVPR | Single Image Reflection Removal Through Cascaded Refinement | \[[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Single_Image_Reflection_Removal_Through_Cascaded_Refinement_CVPR_2020_paper.pdf)\]<br />\[[code](https://github.com/JHL-HUST/IBCLN)\] |
| 2020 | CVPR | Single Image Reflection Removal with Physically-Based Training Images | \[[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kim_Single_Image_Reflection_Removal_With_Physically-Based_Training_Images_CVPR_2020_paper.pdf)\]<br />\[[code](https://github.com/sookim813/Reflection_removal_rendering)\] |
| 2020 | CVPR | Deep Adversarial Decomposition: A Unified Framework for Separating Superimposed Images | \[[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zou_Deep_Adversarial_Decomposition_A_Unified_Framework_for_Separating_Superimposed_Images_CVPR_2020_paper.pdf)\]<br />\[[code](https://github.com/jiupinjia/Deep-adversarial-decomposition)\] |
| 2021 | WACV | Single image reflection removal with edge guidance, reflection classifier, and recurrent decomposition | \[[paper](https://people.cs.nctu.edu.tw/~walon/publications/chang2021wacv.pdf)\]<br />\[[code](https://github.com/JennaChangY/Reflection-Removal-with-Auxiliary-Techniques)\] |
| 2021 | ICCV | Location-aware single image reflection removal | \[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Dong_Location-Aware_Single_Image_Reflection_Removal_ICCV_2021_paper.pdf)\]<br />\[[code](https://github.com/zdlarr/Location-aware-SIRR)\] |
| 2021 | NIPS | Trash or Treasure? An Interactive Dual-Stream Strategy for Single Image Reflection Separation | \[[paper](https://proceedings.neurips.cc/paper/2021/file/cf1f78fe923afe05f7597da2be7a3da8-Paper.pdf)\]<br />\[[code](https://github.com/mingcv/YTMT-Strategy)\] |
| 2021 | CVPR | Single Image Reflection Removal with Absorption Effect | \[[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zheng_Single_Image_Reflection_Removal_With_Absorption_Effect_CVPR_2021_paper.pdf)\]<br />\[[code](https://github.com/q-zh/absorption)\] |
| 2021 | CVPR | Robust Reflection Removal with Reflection-free Flash-only Cues | \[[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lei_Robust_Reflection_Removal_With_Reflection-Free_Flash-Only_Cues_CVPR_2021_paper.pdf)\]<br />\[[code](https://github.com/ChenyangLEI/flash-reflection-removal)\] |
| 2021 | ICCV | V-DESIRR: Very Fast Deep Embedded Single Image Reflection Removal | \[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Prasad_V-DESIRR_Very_Fast_Deep_Embedded_Single_Image_Reflection_Removal_ICCV_2021_paper.pdf)\]<br />\[code\]✖️ |
| 2021 | TIP | Deep-Masking Generative Network: A Unified Framework for Background Restoration from Superimposed Images | \[[paper](https://arxiv.org/pdf/2010.04324v2.pdf)\]<br />\[[code](https://github.com/funkdub/DMGN-Deep-Masking-Generative-Network-TIP2021)\] |
| 2022 | WACV | Improving Single-Image Defocus Deblurring: How Dual-Pixel Images Help Through Multi-Task Learning | [[paper](https://arxiv.org/pdf/2108.05251.pdf)\]<br />\[[code](https://github.com/Abdullah-Abuolaim/multi-task-defocus-deblurring-dual-pixel-nimat)\] |
| 2022 | PAMI | Benchmarking Single-Image Reflection Removal Algorithms | [[paper](https://ieeexplore.ieee.org/document/9760117)\]<br />\[[website](https://sir2data.github.io/)\] |
| 2023 | CVPR | :star2: Robust Single Image Reflection Removal Against Adversarial Attacks | [[paper](https://openaccess.thecvf.com/content/CVPR2023/html/Song_Robust_Single_Image_Reflection_Removal_Against_Adversarial_Attacks_CVPR_2023_paper.html)\]<br />\[ \] |

## Image Quality Assessment

| Method | Type | Code/Ref |
| --- | --- | --- |
| PSNR (Peak Signal-to-Noise Ratio) | Full-Reference | \[[code](https://github.com/XPixelGroup/BasicSR/blob/master/basicsr/metrics/psnr_ssim.py)\] |
| SSIM (Structural Similarity Index Measurement) | Full-Reference | \[[code](https://github.com/XPixelGroup/BasicSR/blob/master/basicsr/metrics/psnr_ssim.py)\] |
| LPIPS (Learned Perceptual Image Patch Similarity) | Full-Reference | \[[code](https://github.com/richzhang/PerceptualSimilarity)\] |

## Benchmark Datasets

**Recommended Datasets**

| Dataset | Usage | Image num |
| --- | --- | --- |
| [SIR<sup>2</sup>](https://drive.google.com/file/d/1A5T1c53CNac5xQ8e1awOUVYiWzUPotDn/view) | Test | 500 |
| [Real20](https://drive.google.com/drive/folders/1NYGL3wQ2pRkwfLMcV2zxXDV8JRSoVxwA) | Training & Test | 89 & 20 |
| [Nature](https://drive.google.com/file/d/1YWkm80jWsjX6XwLTHOsa8zK3pSRalyCg/view) | Test | 200 |
| [CDR](https://github.com/XUHUAKing/CDR-download-scripts) | Test | 1063 |
