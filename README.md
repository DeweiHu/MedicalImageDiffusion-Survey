# Medical Image Diffusion-Survey

This is an updating survey for the application of diffusion probabilistic models on medical image analysis. The current tables include the most recent papers published in **MICCAI 2023**. For more works presented before 2023, refer to the survey paper [Diffusion models for medical image analysis: A comprehensive survey](https://arxiv.org/pdf/2211.07804.pdf) by Kazerouni et al.  

### Synthesis
We classify the image synthesis works into several categories: semantic, modality/style transfer, 2D to 3D generation, image enhancement/denoising, and super-resolution. 

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
| 9 |Make-A-Volume: Leveraging Latent Diffusion Models for Cross-Modality 3D Brain MRI Synthesis [pdf](https://arxiv.org/pdf/2307.10094.pdf) | 2D to 3D |  | MRI | latent |
| 10 |Generating Realistic Brain MRIs via a Conditional Diffusion Probabilistic Model [link](https://link.springer.com/chapter/10.1007/978-3-031-43993-3_2) | 2D to 3D | [link](https://github.com/xiaoiker/mask3DMRI_diffusion) | MRI | image |
| 11 |PET-diffusion: Unsupervised PET Enhancement based on the Latent Diffusion Model [link](https://link.springer.com/chapter/10.1007/978-3-031-43907-0_1) | Denoising/Enhancement |  | PET | latent |
| 12 |Pre-trained Diffusion Models for Plug-and-Play Medical Image Enhancement [link](https://link.springer.com/chapter/10.1007/978-3-031-43898-1_1) | Denoising/Enhancement |  | CT\MRI | image |
| 13 |Content-Preserving Diffusion Model for Unsupervised AS-OCT image Despeckling [pdf](https://arxiv.org/pdf/2306.17717.pdf) | Denoising/Enhancement |  | OCT | image |
| 14 |PET Image Denoising with Score-Based Diffusion Probabilistic Models [link](https://link.springer.com/chapter/10.1007/978-3-031-43907-0_26) | Denoising/Enhancement |  | PET | image |
| 15 |DisC-Diff: Disentangled Conditional Diffusion Model for Multi-Contrast MRI Super-Resolution [pdf](https://arxiv.org/pdf/2303.13933.pdf) | Super-resolution | [link](https://github.com/Yebulabula/DisC-Diff) | MRI | image |
| 16 |InverseSR: 3D Brain MRI Super-Resolution Using a Latent Diffusion Model [pdf](https://arxiv.org/pdf/2308.12465.pdf) | Super-resolution | [link](https://github.com/BioMedAI-UCSC/InverseSR) | MRI | latent |
| 17 |Topology-Preserving Computed Tomography Super-resolution Based on Dual-stream Diffusion Model [link](https://link.springer.com/chapter/10.1007/978-3-031-43999-5_25) | Super-resolution | [link](https://github.com/Arturia-Pendragon-Iris/UHRCT_SR) | CT | image |

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
