# Medical Image Diffusion-Survey

This is an updating survey for the application of diffusion probabilistic models on medical image analysis. The current tables include the most recent papers published in **MICCAI 2023**. For more works presented before 2023, refer to the survey paper [Diffusion models for medical image analysis: A comprehensive survey](https://arxiv.org/pdf/2211.07804.pdf) by Kazerouni et al.  

### Synthesis
We classify the image synthesis works into several categories: semantic, modality/style transfer, 3D generation, image enhancement/denoising, and super-resolution. 

| | Paper Title | Category | Code | Modality | DM |
| :--: | :--------- | :-----: | :-----: | :-----: | :-----: |
| 1 |ArSDM: Colonoscopy Images Synthesis with Adaptive Refinement Semantic Diffusion Models [pdf](https://arxiv.org/pdf/2309.01111.pdf) | Semantic | [link](https://github.com/DuYooho/ArSDM) | Colonoscopy | image |
| 2 |NASDM: Nuclei-Aware Semantic Histopathology Image Generation Using Diffusion Models [pdf](https://arxiv.org/pdf/2303.11477.pdf) | Semantic |  | Histology | image |
| 3 |Diffusion-based Data Augmentation for Nuclei Image Segmentation [pdf](https://arxiv.org/pdf/2310.14197.pdf) | Semantic |  | Histology | image |
| 4 |DiffMix: Diffusion Model-based Data Synthesis for Nuclei Segmentation and Classification in Imbalanced Pathology Image Datasets [pdf](https://arxiv.org/pdf/2306.14132.pdf) | Semantic |  | Histology | image |
| 5 |Artifact Restoration in Histology Images with Diffusion Probabilistic Models [pdf](https://arxiv.org/pdf/2307.14262.pdf) | Semantic | [link](https://github.com/zhenqi-he/ArtiFusion) | Histology | image |
| 6 |CoLa-Diff: Conditional Latent Diffusion Model for Multi-Modal MRI Synthesis [pdf](https://arxiv.org/pdf/2303.14081.pdf) | Modality/Style Transfer |  | MRI | latent |
| 7 |UXDiff: Synthesis of X-ray Image from Ultrasound Coronal Image of Spine with Diffusion Probabilistic Network [link](https://link.springer.com/chapter/10.1007/978-3-031-43996-4_1) | Modality/Style Transfer |  | Ultrasound/X-ray | image |
| 8 |StainDiff: Transfer Stain Styles of Histology Images with Denoising Diffusion Probabilistic Models and Self-Ensemble [link](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_53) | Modality/Style Transfer |  | Histology | image |
| 9 |Synthesising Rare Cataract Surgery Samples with Guided Diffusion Models [pdf](https://arxiv.org/pdf/2308.02587.pdf) | Modality/Style Transfer | [link](https://github.com/MECLabTUDA/CataSynth) | Cataract Surgery | image |
| 10 |Make-A-Volume: Leveraging Latent Diffusion Models for Cross-Modality 3D Brain MRI Synthesis [pdf](https://arxiv.org/pdf/2307.10094.pdf) | 3D generation |  | MRI | latent |
| 11 |Generating Realistic Brain MRIs via a Conditional Diffusion Probabilistic Model [link](https://link.springer.com/chapter/10.1007/978-3-031-43993-3_2) | 3D generation | [link](https://github.com/xiaoiker/mask3DMRI_diffusion) | MRI | image |
| 12 |Generating High-Resolution 3D CT with 12-bit Depth using a Diffusion Model with Adjacent Slice and Intensity Calibration Network [link](https://link.springer.com/chapter/10.1007/978-3-031-43999-5_35) | 3D generation |  | CT | image |
| 13 |Point Cloud Diffusion Models for Automatic Implant Generation [link](https://link.springer.com/chapter/10.1007/978-3-031-43996-4_11) | 3D generation | [link](https://pfriedri.github.io/pcdiff-implant-io/) | CT | image |
| 14 |Feature-Conditioned Cascaded Video Diffusion Models for Precise Echocardiogram Synthesis [pdf](hhttps://arxiv.org/pdf/2303.12644.pdf) | 3D generation | [link](https://github.com/HReynaud/EchoDiffusion) | Ultrasound | image |
| 15 |PET-diffusion: Unsupervised PET Enhancement based on the Latent Diffusion Model [link](https://link.springer.com/chapter/10.1007/978-3-031-43907-0_1) | Denoising/Enhancement | [link](https://github.com/jiang-cw/PET-diffusion) | PET | latent |
| 16 |Pre-trained Diffusion Models for Plug-and-Play Medical Image Enhancement [link](https://link.springer.com/chapter/10.1007/978-3-031-43898-1_1) | Denoising/Enhancement | [link](https://github.com/bowang-lab/DPM-MedImgEnhance) | CT\MRI | image |
| 17 |Content-Preserving Diffusion Model for Unsupervised AS-OCT image Despeckling [pdf](https://arxiv.org/pdf/2306.17717.pdf) | Denoising/Enhancement |  | OCT | image |
| 18 |PET Image Denoising with Score-Based Diffusion Probabilistic Models [link](https://link.springer.com/chapter/10.1007/978-3-031-43907-0_26) | Denoising/Enhancement |  | PET | image |
| 19 |DisC-Diff: Disentangled Conditional Diffusion Model for Multi-Contrast MRI Super-Resolution [pdf](https://arxiv.org/pdf/2303.13933.pdf) | Super-resolution | [link](https://github.com/Yebulabula/DisC-Diff) | MRI | image |
| 20 |InverseSR: 3D Brain MRI Super-Resolution Using a Latent Diffusion Model [pdf](https://arxiv.org/pdf/2308.12465.pdf) | Super-resolution | [link](https://github.com/BioMedAI-UCSC/InverseSR) | MRI | latent |
| 21 |Topology-Preserving Computed Tomography Super-resolution Based on Dual-stream Diffusion Model [link](https://link.springer.com/chapter/10.1007/978-3-031-43999-5_25) | Super-resolution | [link](https://github.com/Arturia-Pendragon-Iris/UHRCT_SR) | CT | image |

### Segmentation

| | Paper Title | Code | Modality | DM |
| :--: | :------------- | :-----: | :-----: | :-----: |
| 1 | BerDiff: Conditional Bernoulli Diffusion Model for Medical Image Segmentation [pdf](https://arxiv.org/pdf/2304.04429.pdf) |  | MRI/CT | image |
| 2 | Conditional Diffusion Models for Weakly Supervised Medical Image Segmentation [pdf](https://arxiv.org/pdf/2306.03878.pdf) |  | MRI | image |
| 3 | Diffusion Kinetic Model for Breast Cancer Segmentation in Incomplete DCE-MRI [link](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_10) |  | MRI | image |
| 4 | Diffusion Transformer U-Net for Medical Image Segmentation [link](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_59) |  | Colonoscopy/Dermoscopy/Fundus | image |
| 5 | FEDD - Fair, Efficient, and Diverse Diffusion-based Lesion Segmentation and Malignancy Classification [pdf](https://arxiv.org/pdf/2307.11654.pdf) | [link](https://github.com/hectorcarrion/fedd) | Dermoscopy | image |
| 6 | Instance-Aware Diffusion Model for Gland Segmentation in Colon Histology Images [link](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_64) |  | Histology | image |
| 7 | Learning Reliability of Multi-Modality Medical Images for Tumor Segmentation via Evidence-Identified Denoising Diffusion Probabilistic Models [link](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_65) |  | MRI | image |
| 8 | Medical Boundary Diffusion Model for Skin Lesion Segmentation [link](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_41) | [link](https://github.com/jcwang123/MBDiff) | Dermoscopy | image |


### Reconstruction
| | Paper Title | Code | Modality | DM |
| :--: | :------------- | :-----: | :-----: | :-----: |
| 1 | Contrastive Diffusion Model with Auxiliary Guidance for Coarse-to-Fine PET Reconstruction [pdf](https://arxiv.org/pdf/2308.10157.pdf) | [link](https://github.com/Show-han/PET-Reconstruction) | PET | image |
| 2 | DMCVR: Morphology-Guided Diffusion Model for 3D Cardiac Volume Reconstruction [pdf](https://arxiv.org/pdf/2308.09223.pdf) | [link](https://github.com/hexiaoxiao-cs/DMCVR) | MRI | image |
| 3 | DiffuseIR: Diffusion Models For Isotropic Reconstruction of 3D Microscopic Images [pdf](https://arxiv.org/pdf/2306.12109.pdf) |  | Microscopy | image |
| 4 | Self-Supervised MRI Reconstruction with Unrolled Diffusion Models [pdf](https://arxiv.org/pdf/2306.16654.pdf) | [link](https://github.com/yilmazkorkmaz1/SSDiffRecon) | MRI | image |
| 5 | SMRD: SURE-based Robust MRI Reconstruction with Diffusion Models [pdf](https://arxiv.org/pdf/2310.01799.pdf) | [link](https://github.com/NVlabs/SMRD) | MRI | image |


### Out-of-distribution Detection
| | Paper Title | Code | Modality | DM |
| :--: | :--------- | :-----: | :-----: | :-----: |
| 1 | Dual Conditioned Diffusion Models for Out-Of-Distribution Detection: Application to Fetal Ultrasound Videos [pdf](https://arxiv.org/pdf/2311.00469.pdf) |  | Ultrasound | latent |
| 2 | Fast Non-Markovian Diffusion Model for Weakly Supervised Anomaly Detection in Brain MR Images [link](https://link.springer.com/chapter/10.1007/978-3-031-43904-9_56) |  | MRI | image |
| 3 | Unsupervised 3D out-of-distribution detection with latent diffusion models [pdf](https://arxiv.org/pdf/2307.03777.pdf) | [link](https://github.com/marksgraham/ddpm-ood) | CT | latent |


### Classification
| | Paper Title | Code | Modality | DM |
| :--: | :--------- | :-----: | :-----: | :-----: |
| 1 | DiffMIC: Dual-Guidance Diffusion Network for Medical Image Classification [pdf](https://arxiv.org/pdf/2303.10610.pdf) | [link](https://github.com/scott-yjyang/DiffMIC) | --- | latent |
| 2 | Unsupervised classification of congenital inner ear malformations using DeepDiffusion for latent space representation [pdf](https://backend.orbit.dtu.dk/ws/portalfiles/portal/332404520/paper2309.pdf) | [link](https://github.com/paulalopez10/Deep-Diffusion-Unsupervised-Classification-3D-Mesh) | CT | latent |


### Others
| | Paper Title | Category | Code | Modality | DM |
| :--: | :--------- | :-----: | :-----: | :-----: | :-----: |
| 1 | FSDiffReg: Feature-wise and Score-wise Diffusion-guided Unsupervised Deformable Image Registration for Cardiac Images [pdf](https://arxiv.org/pdf/2307.12035.pdf) | Registration | [link](https://github.com/xmed-lab/FSDiffReg) | MRI | image |
| 2 | DiffDP: Radiotherapy Dose Prediction via a Diffusion Model [pdf](https://arxiv.org/pdf/2307.09794.pdf) | Regression | [link](https://github.com/xmed-lab/FSDiffReg) | CT | image |
