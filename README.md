<img src="https://github.com/CV-AC/Awesome-FaceDe-ID/blob/main/assets/teaser.jpeg?raw=true" width=100%>

# Awesome Face De-Identification
 ![Awesome](https://awesome.re/badge.svg) ![visitors](https://visitor-badge.laobi.icu/badge?page_id=cv-ac.awesome-facede-id)
 
A comprehensive collection of face de-identification (De-ID) research papers. Star ⭐ this repository if you find it helpful! If you find any omitted literature or source code, please feel free to submit issues for addition.

> Based on the survey paper: **Face De-Identification: A Domain-Centric Survey from Capture to Processing**  
> Authors: *Hui Wei, Hao Yu, and Guoying Zhao*

The awesome face De-ID repository adopts a **domain-centric** taxonomy that categorizes approaches into three classes: physical, sensor, and digital.
<img src="https://github.com/CV-AC/Awesome-FaceDe-ID/blob/main/assets/fdeid.png?raw=true" width=60%>

## 📋Table of Contents
- [Survey Papers](#survey-papers)
- [Datasets](#datasets)
- [Physical Domain Methods](#physical-domain-methods)
- [Sensor Domain Methods](#sensor-domain-methods)
- [Digital Domain Methods](#digital-domain-methods)

## 📑Survey Papers
- **[2025]** Toward a Privacy-Preserving Face Recognition System: A Survey of Leakages and Solutions. [PDF](https://dl.acm.org/doi/full/10.1145/3673224). ACM CSUR.
- **[2025]** Person De-Identification: A Comprehensive Review of Methods, Datasets, Applications, and Ethical Aspects Along With New Dimensions. [PDF](https://ieeexplore.ieee.org/abstract/document/10734402). IEEE TBIOM.
- **[2025]** Faces in the Fog: A Deep Dive into Face De-Identification Techniques and Their Comparative Analysis. [PDF](https://ieeexplore.ieee.org/abstract/document/10986474). DICCT.
- **[2024]** Face De-identification: State-of-the-art Methods and Comparative Studies. [PDF](https://arxiv.org/abs/2411.09863). arXiv. 
- **[2023]** Presentation-level Privacy Protection Techniques for Automated Face Recognition—A Survey. [PDF](https://dl.acm.org/doi/full/10.1145/3583135). ACM CSUR.
- **[2022]** Privacy Intelligence: A Survey on Image Privacy in Online Social Networks. [PDF](https://dl.acm.org/doi/full/10.1145/3547299). ACM CSUR.
- **[2022]** Benchmarking 3D Face De-Identification with Preserving Facial Attributes. [PDF](https://ieeexplore.ieee.org/abstract/document/9897232). IEEE ICIP.
- **[2015]** An Overview of Face De-identification in Still Images and Videos. [PDF](https://ieeexplore.ieee.org/abstract/document/7285017). IEEE FG.

## 💾Datasets
- **LFW (Labeled Faces in the Wild):** The most prevalent benchmark for identity variance and pose diversity.
- **VGGFace2:** Offers superior diversity with 9k+ identities and 3.31M images.
- **FFHQ:** High-quality dataset frequently used for StyleGAN-based methods.
- **CelebA / CelebA-HQ:** Large-scale attribute annotations, dominant in generative De-ID evaluation.
- **RaFD / AffectNet:** For emotion and expression preservation evaluation.
- **Bosphorus / BU-3DFE:** For 3D-aware face De-ID methods.
- **PURE / OBF:** For rPPG physiological signal preservation.


## 😃Physical Domain Methods
- **[2025]** Face3DAdv: Exploiting Robust Adversarial 3D Patches on Physical Face Recognition. [PDF](https://link.springer.com/article/10.1007/s11263-024-02177-6). IJCV.
- **[2025]** ProjAttacker: A Configurable Physical Adversarial Attack for Face Recognition via Projector. [PDF](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_ProjAttacker_A_Configurable_Physical_Adversarial_Attack_for_Face_Recognition_via_CVPR_2025_paper.html). *CVPR*.
- **[2024]** Adversarial Relighting Against Face Recognition. [PDF](https://ieeexplore.ieee.org/abstract/document/10478138). *TIFS*.
- **[2024]** The Invisible Polyjuice Potion: an Effective Physical Adversarial Attack against Face Recognition. [PDF](https://dl.acm.org/doi/abs/10.1145/3658644.3670382) | [Code](https://github.com/LaserFR/LaserFR). *ACM SIGSAC*.
- **[2024]** Stealthy Physical Masked Face Recognition Attack via Adversarial Style Optimization. [PDF](https://ieeexplore.ieee.org/abstract/document/10306334) | [Code](https://github.com/small-seven/sasmask). *IEEE TMM*.
- **[2023]** Physical-World Optical Adversarial Attacks on 3D Face Recognition. [PDF](https://openaccess.thecvf.com/content/CVPR2023/html/Li_Physical-World_Optical_Adversarial_Attacks_on_3D_Face_Recognition_CVPR_2023_paper.html) | [Code](https://github.com/PolyLiYJ/SLAttack). *CVPR*.
- **[2023]** Towards Effective Adversarial Textured 3D Meshes on Physical Face Recognition. [PDF](https://openaccess.thecvf.com/content/CVPR2023/html/Yang_Towards_Effective_Adversarial_Textured_3D_Meshes_on_Physical_Face_Recognition_CVPR_2023_paper.html) | [Code](https://github.com/thu-ml/AT3D). *CVPR*.
- **[2023]** Simultaneously Optimizing Perturbations and Positions for Black-Box Adversarial Patch Attacks. [PDF](https://ieeexplore.ieee.org/abstract/document/9999043) | [Code](https://github.com/shighghyujie/newpatch-rl). *IEEE TPAMI*.
- **[2022]** Adversarial Mask: Real-World Universal Adversarial Attack on Face Recognition Models. [PDF](https://link.springer.com/chapter/10.1007/978-3-031-26409-2_19) | [Code](https://github.com/AlonZolfi/AdversarialMask). *ECML PKDD*.
- **[2022]** Powerful Physical Adversarial Examples Against Practical Face Recognition Systems. [PDF](https://ieeexplore.ieee.org/document/9707528). *WACV*.
- **[2022]** Adversarial Sticker: A Stealthy Attack Method in the Physical World. [PDF](https://ieeexplore.ieee.org/abstract/document/9779913) | [Code](https://github.com/jinyugy21/Adv-Stickers_RHDE). *IEEE TPAMI*.
- **[2021]** Improving Transferability of Adversarial Patches on Face Recognition with Generative Models. [PDF](https://openaccess.thecvf.com/content/CVPR2021/papers/Xiao_Improving_Transferability_of_Adversarial_Patches_on_Face_Recognition_With_Generative_CVPR_2021_paper.pdf). *CVPR*.
- **[2021]** Effective and Robust Physical-World Attacks on Deep Learning Face Recognition Systems. [PDF](https://ieeexplore.ieee.org/document/9505665) | [Code](https://github.com/csyuhao/FaceAdv). *TIFS*.
- **[2021]** Adv-Makeup: A New Imperceptible and Transferable Attack on Face Recognition. [PDF](https://www.ijcai.org/proceedings/2021/0173.pdf) | [Code](https://github.com/TencentYoutuResearch/Adv-Makeup). *IJCAI*.
- **[2020]** AdvHat: Real-World Adversarial Attack on ArcFace Face ID System. [PDF](https://arxiv.org/abs/1908.08705) | [Code](https://github.com/papermsucode/advhat). *ICPR*.
- **[2020]** Adversarial Light Projection Attacks on Face Recognition Systems: A Feasibility Study. [PDF](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w48/Nguyen_Adversarial_Light_Projection_Attacks_on_Face_Recognition_Systems_A_Feasibility_CVPRW_2020_paper.pdf). *CVPRW*.
- **[2019]** A General Framework for Adversarial Examples with Objectives. [PDF](https://dl.acm.org/doi/10.1145/3317611) | [Code](https://github.com/mahmoods01/agns). *ACM TOPS*.
- **[2016]** Accessorize to a Crime: Real and Stealthy Attacks on State-of-the-Art Face Recognition. [PDF](https://dl.acm.org/doi/10.1145/2976749.2978392) | [Code](https://github.com/mahmoods01/accessorize-to-a-crime). ACM CCS.

## 📷Sensor Domain Methods
- **[2024]** Privacy-Preserving Optics for Enhancing Protection in Face De-Identification. [PDF](https://openaccess.thecvf.com/content/CVPR2024/papers/Lopez_Privacy-Preserving_Optics_for_Enhancing_Protection_in_Face_De-Identification_CVPR_2024_paper.pdf). *CVPR*.
- **[2024]** Learning a Dynamic Privacy-Preserving Camera Robust to Inversion Attacks. [PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08911.pdf). *ECCV*.
- **[2024]** OpticalDR: A Deep Optical Imaging Model for Privacy-Protective Depression Recognition. [PDF](https://openaccess.thecvf.com/content/CVPR2024/papers/Pan_OpticalDR_A_Deep_Optical_Imaging_Model_for_Privacy-Protective_Depression_Recognition_CVPR_2024_paper.pdf) | [Code](https://github.com/divertingPan/OpticalDR). *CVPR*.
- **[2022]** Learning Phase Mask for Privacy-Preserving Passive Depth Estimation. [PDF](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/7139_ECCV_2022_paper.php). *ECCV*.
- **[2022]** PrivHAR: Recognizing Human Actions from Privacy-Preserving Lens. [PDF](https://carloshinojosa.me/files/ECCV2022PrivHAR/5080.pdf). *ECCV*.
- **[2021]** Learning Privacy-preserving Optics for Human Pose Estimation. [PDF](https://openaccess.thecvf.com/content/ICCV2021/papers/Hinojosa_Learning_Privacy-Preserving_Optics_for_Human_Pose_Estimation_ICCV_2021_paper.pdf) | [Code](https://github.com/carlosh93/privacy-optics-hpe). *ICCV*.
- **[2018]** Extreme Low Resolution Activity Recognition with Multi-Siamese Embedding Learning. [PDF](https://cdn.aaai.org/ojs/12299/12299-13-15827-1-2-20201228.pdf). *AAAI*.
- **[2018]** Privacy-Preserving Human Activity Recognition from Extreme Low Resolution. [PDF](https://arxiv.org/abs/1604.03196). *AAAI*.
- **[2017]** Pre-Capture Privacy for Small Vision Sensors. [PDF](https://ieeexplore.ieee.org/document/7778202). *IEEE TPAMI*.
- **[2015]** Privacy Preserving Optics for Miniature Vision Sensors. [PDF](https://ieeexplore.ieee.org/document/7298628). *CVPR*.

## 💻Digital Domain Methods
- **[2025]** Face-DeID-Net: Generative Face De-Identification with Identity Removal and Attribute Preservation for Latent Diffusion Model Training. [PDF](https://ieeexplore.ieee.org/document/11171560). *ICSIP*.
- **[2025]** 3D Face De-Identification With Preserving Multi-Facial Attributes: A Benchmark. [PDF](https://ieeexplore.ieee.org/document/11005387) | [Code](https://github.com/kevinhmcheng/3d-face-de-id). *IEEE TBIOM*.
- **[2025]** Face Anonymization Made Simple. [PDF](https://openaccess.thecvf.com/content/WACV2025/papers/Kung_Face_Anonymization_Made_Simple_WACV_2025_paper.pdf) | [Code](https://github.com/hanweikung/face_anon_simple). *WACV*.
- **[2025]** Facial Identity Editing: Towards Effective De-Identification. [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11084682). *ICIP*.
- **[2025]** Balancing Privacy and Performance: A Many-in-One Approach for Image Anonymization. [PDF](https://dl.acm.org/doi/10.1609/aaai.v39i17.33936). *AAAI*.
- **[2025]** Adv-Inversion: Stealthy Adversarial Attacks via GAN-Inversion for Facial Privacy Protection. [PDF](https://ieeexplore.ieee.org/document/11218144). *TIFS*.
- **[2025]** Adv-CPG: A Customized Portrait Generation Framework with Facial Adversarial Attacks. [PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_Adv-CPG_A_Customized_Portrait_Generation_Framework_with_Facial_Adversarial_Attacks_CVPR_2025_paper.pdf) | [Code](https://github.com/JunyingWang959/Adv-CPG). *CVPR*.
- **[2025]** Enhancing Facial Privacy Protection via Weakening Diffusion Purification. [PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Salar_Enhancing_Facial_Privacy_Protection_via_Weakening_Diffusion_Purification_CVPR_2025_paper.pdf) | [Code](https://github.com/parham1998/Facial-Privacy-Protection). *CVPR*.
- **[2025]** Improving the Transferability of Adversarial Attacks on Face Recognition with Diverse Parameters Augmentation. [PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhou_Improving_the_Transferability_of_Adversarial_Attacks_on_Face_Recognition_with_CVPR_2025_paper.pdf) | [Code](https://github.com/fengfanzhou/DPA). *CVPR*.
- **[2024]** Personalized Privacy Protection Mask Against Unauthorized Facial Recognition. [PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10846.pdf) | [Code](https://github.com/git-disl/Chameleon). *ECCV*.
- **[2024]** Disguise without Disruption: Utility-Preserving Face De-Identification. [PDF](https://arxiv.org/abs/2303.13269). *AAAI*.
- **[2024]** DiffAM: Diffusion-based Adversarial Makeup Transfer for Facial Privacy Protection. [PDF](https://openaccess.thecvf.com/content/CVPR2024/papers/Sun_DiffAM_Diffusion-based_Adversarial_Makeup_Transfer_for_Facial_Privacy_Protection_CVPR_2024_paper.pdf) | [Code](https://github.com/HansSunY/DiffAM). *CVPR*.
- **[2024]** Veil Privacy on Visual Data: Concealing Privacy for Humans, Unveiling for DNNs. [PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/11044.pdf). *ECCV*.
- **[2024]** GANonymization: A GAN-Based Face Anonymization Framework for Preserving Emotional Expressions. [PDF](https://dl.acm.org/doi/10.1145/3641107) | [Code](https://github.com/hcmlab/GANonymization). *IEEE TMCCA*.
- **[2023]** Achieving Privacy-Preserving Multi-View Consistency with Advanced 3D-Aware Face De-identification. [PDF](https://dl.acm.org/doi/10.1145/3595916.3626407). *ACM MM Asia*.
- **[2023]** Towards Face De-identification for Wearable Cameras. [PDF](https://dl.acm.org/doi/10.1145/3617233.3617276). *ICMI*.
- **[2023]** Discrete Point-Wise Attack Is Not Enough: Generalized Manifold Adversarial Attack for Face Recognition. [PDF](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Discrete_Point-Wise_Attack_Is_Not_Enough_Generalized_Manifold_Adversarial_Attack_CVPR_2023_paper.pdf) | [Code](https://github.com/tokaka22/CVPR23-GMAA). *CVPR*.
- **[2023]** Transferable Black-Box Attack Against Face Recognition With Spatial Mutable Adversarial Patch. [PDF](https://ieeexplore.ieee.org/document/10234435). *TIFS*.
- **[2023]** Sibling-Attack: Rethinking Transferable Adversarial Attacks Against Face Recognition. [PDF](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Sibling-Attack_Rethinking_Transferable_Adversarial_Attacks_Against_Face_Recognition_CVPR_2023_paper.pdf). *CVPR*.
- **[2023]** DiffProtect: Generate Adversarial Examples with Diffusion Models for Facial Privacy Protection. [PDF](https://arxiv.org/abs/2305.13625) | [Code](https://github.com/joellliu/DiffProtect/). *arXiv*.
- **[2023]** CLIP2Protect: Protecting Facial Privacy Using Text-Guided Makeup via Adversarial Latent Search. [PDF](https://openaccess.thecvf.com/content/CVPR2023/papers/Shamshad_CLIP2Protect_Protecting_Facial_Privacy_Using_Text-Guided_Makeup_via_Adversarial_Latent_CVPR_2023_paper.pdf) | [Code](https://github.com/fahadshamshad/Clip2Protect). *CVPR*.
- **[2023]** Face Image De-Identification by Feature Space Adversarial Perturbation. [PDF](https://onlinelibrary.wiley.com/doi/full/10.1002/cpe.7554). *CCPE*.
- **[2022]** Protecting Facial Privacy: Generating Adversarial Identity Masks via Style-robust Makeup Transfer. [PDF](https://openaccess.thecvf.com/content/CVPR2022/papers/Hu_Protecting_Facial_Privacy_Generating_Adversarial_Identity_Masks_via_Style-Robust_Makeup_CVPR_2022_paper.pdf) | [Code](https://github.com/CGCL-codes/AMT-GAN). *CVPR*.
- **[2022]** Adv-Attribute: Inconspicuous and Transferable Adversarial Attack on Face Recognition. [PDF](https://papers.neurips.cc/paper_files/paper/2022/file/dccbeb7a8df3065c4646928985edf435-Paper-Conference.pdf). *NeurIPS*.
- **[2022]** IdentityMask: Deep Motion Flow Guided Reversible Face Video De-Identification. [PDF](https://ieeexplore.ieee.org/document/9832607). *IEEE TCSVT*.
- **[2021]** Effective De-identification Generative Adversarial Network for Face Anonymization. [PDF](https://dl.acm.org/doi/10.1145/3474085.3475464). *ACM MM*.
- **[2021]** Identity-Preserving Face Anonymization via Adaptively Facial Attributes Obfuscation. [PDF](https://dl.acm.org/doi/abs/10.1145/3474085.3475367) | [Code](https://github.com/RuoyuChen10/Facial_Attributes_Obfuscation). *ACM MM*.
- **[2021]** Towards Face Encryption by Generating Adversarial Identity Masks. [PDF](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Towards_Face_Encryption_by_Generating_Adversarial_Identity_Masks_ICCV_2021_paper.pdf) | [Code](https://github.com/ShawnXYang/TIP-IM). *ICCV*.
- **[2020]** Towards Transferable Adversarial Attack Against Deep Face Recognition. [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9252132). *TIFS*.
- **[2020]** AdvFaces: Adversarial Face Synthesis. [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9304898) | [Code](https://github.com/ronny3050/AdvFaces). *IJCB*.
- **[2020]** CIAGAN: Conditional Identity Anonymization Generative Adversarial Networks. [PDF](https://openaccess.thecvf.com/content_CVPR_2020/papers/Maximov_CIAGAN_Conditional_Identity_Anonymization_Generative_Adversarial_Networks_CVPR_2020_paper.pdf) | [Code](https://github.com/dvl-tum/ciagan). *CVPR*.
- **[2019]** AnonymousNet: Natural Face De-Identification With Measurable Privacy. [PDF](https://openaccess.thecvf.com/content_CVPRW_2019/papers/CV-COPS/Li_AnonymousNet_Natural_Face_De-Identification_With_Measurable_Privacy_CVPRW_2019_paper.pdf). *CVPRW*.
- **[2019]** Efficient Decision-based Black-box Adversarial Attacks on Face Recognition. [PDF](https://openaccess.thecvf.com/content_CVPR_2019/papers/Dong_Efficient_Decision-Based_Black-Box_Adversarial_Attacks_on_Face_Recognition_CVPR_2019_paper.pdf) | [Code](https://github.com/sgmath12/efficient-decision-based-black-box-adversarial-attacks-on-face-recognition). *CVPR*.
- **[2019]** Attributes Preserving Face De-Identification. [PDF](https://ieeexplore.ieee.org/document/9022403). *ICCVW*.
- **[2017]** I Know That Person: Generative Full Body and Face De-identification of People in Images. [PDF](https://www.computer.org/csdl/proceedings-article/cvprw/2017/0733b319/12OmNBKmXhH). *CVPRW*.
- **[2015]** Face De-identification Using Facial Identity Preserving Features. [PDF](https://ieeexplore.ieee.org/document/7418263). *GlobalSIP*.
- **[2015]** Attribute Preserved Face De-identification. [PDF](https://ieeexplore.ieee.org/document/7139096). *ICB*.
- **[2015]** Face De-identification with Expressions Preservation. [PDF](https://ieeexplore.ieee.org/document/7351631). *ICIP*.
- **[2014]** Photorealistic Face De-Identification by Aggregating Donors’ Face Components. [PDF](https://link.springer.com/chapter/10.1007/978-3-319-16811-1_11). *ACCV*.
- **[2014]** An Approach to the De-Identification of Faces in Different Poses. [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6859758). *ICICTEM*.
- **[2014]** GARP-Face: Balancing Privacy Protection and Utility Preservation in Face De-identification. [PDF](https://ieeexplore.ieee.org/document/6996249). *IJCB*.
- **[2014]** Face De-identification with Perfect Privacy Protection. [PDF](https://ieeexplore.ieee.org/document/6859756). *MIPRO*.
- **[2008]** Semi-Supervised Learning of Multi-Factor Models for Face De-Identification. [PDF](https://ieeexplore.ieee.org/document/4587369). *CVPR*.
- **[2007]** Towards Real-World Face De-Identification. [PDF](https://ieeexplore.ieee.org/document/4401915). *BTAS*.
- **[2006]** Model-Based Face De-Identification. [PDF](https://ieeexplore.ieee.org/document/1640608). *CVPRW*.
- **[2006]** Blur Filtration Fails to Preserve Privacy for Home-based Video Conferencing. [PDF](https://dl.acm.org/doi/10.1145/1143518.1143519). *ACM TOCHI*.
- **[2005]** Preserving Privacy by De-identifying Face Images. [PDF](https://ieeexplore.ieee.org/document/1377174). *IEEE TKDE*.
- **[2000]** The Effects of Filtered Video on Awareness and Privacy. [PDF](https://dl.acm.org/doi/10.1145/358916.358935). *CSCW*.
- **[1996]** Techniques for Addressing Fundamental Privacy and Disruption Tradeoffs in Awareness Support Systems. [PDF](https://dl.acm.org/doi/10.1145/240080.240295). *CSCW*.
