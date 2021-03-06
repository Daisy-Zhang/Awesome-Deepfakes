# Awesome Deepfakes![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

A list of Deepfakes datasets, tools, papers and code. If this list help you in your research, a star is my pleasure.

If you want to contribute to this list, welcome to send me a pull request or contact me :) .

This repo only collect papers related to Deepfake Generation. If you are also interested in Deepfake Detection, please refer to: [Awesome Deepfakes Detection](https://github.com/Daisy-Zhang/awesome-deepfakes-detection).



## Table of Contents

* [Datasets](#datasets)
  * [Video Datasets](#video-datasets)
  * [Image Datasets](#image-datasets)
* [Tools](#tools)
* [Papers](#papers)
  * [CVPR](#cvpr)
  * [ICCV](#iccv)
  * [ECCV](#eccv)
  * [ICLR](#iclr)
  * [IJCAI](#ijcai)
  * [AAAI](#aaai)
  * [ACM MM](#acm-mm)
  * [TPAMI](#tpami)



## Datasets

### Video Datasets

* **UADFV**: "Exposing Deep Fakes Using Inconsistent Head Poses." [Paper](https://arxiv.org/abs/1811.00661)
* **EBV**: "In Ictu Oculi: Exposing AI Generated Fake Face Videos by Detecting Eye Blinking." [Paper](https://arxiv.org/abs/1806.02877)    [Download](http://www.cs.albany.edu/~lsw/downloads.html)
* **Deepfake-TIMIT**: "DeepFakes: a New Threat to Face Recognition? Assessment and Detection." [Paper](https://arxiv.org/abs/1812.08685)    [Download](https://conradsanderson.id.au/vidtimit/)
* **DFFD**: "DFFD: Diverse Fake Face Dataset." [Paper](http://cvlab.cse.msu.edu/dffd-diverse-fake-face-dataset.html)    [Download](http://cvlab.cse.msu.edu/dffd-dataset.html)
* **Wild Deepfake**: "WildDeepfake: A Challenging Real-World Dataset for Deepfake Detection." [Paper](https://arxiv.org/abs/2101.01456)    [Download](https://github.com/deepfakeinthewild/deepfake-in-the-wild)
* **Celeb-DF (v1)**: "Celeb-DF: A Large-scale Challenging Dataset for DeepFake Forensics." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Celeb-DF_A_Large-Scale_Challenging_Dataset_for_DeepFake_Forensics_CVPR_2020_paper.pdf)    [Download](https://github.com/yuezunli/celeb-deepfakeforensics/tree/master/Celeb-DF-v1)
* **Celeb-DF (v2)**: "Celeb-DF: A Large-scale Challenging Dataset for DeepFake Forensics." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Celeb-DF_A_Large-Scale_Challenging_Dataset_for_DeepFake_Forensics_CVPR_2020_paper.pdf)    [Download](https://github.com/yuezunli/celeb-deepfakeforensics/tree/master/Celeb-DF-v2)
* **DFDC**: "The DeepFake Detection Challenge (DFDC) Dataset." [Paper](https://arxiv.org/abs/2006.07397)    [Download](https://www.kaggle.com/c/deepfake-detection-challenge/data) 
* **Deeper Forensic**: "DeeperForensics-1.0: A Large-Scale Dataset for Real-World Face Forgery Detection." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Jiang_DeeperForensics-1.0_A_Large-Scale_Dataset_for_Real-World_Face_Forgery_Detection_CVPR_2020_paper.pdf)    [Download](https://github.com/EndlessSora/DeeperForensics-1.0)
* **FaceForensic++**: "FaceForensics++: Learning to Detect Manipulated Facial Images." [Paper](https://arxiv.org/abs/1901.08971)    [Download](https://github.com/ondyari/FaceForensics)
* **DFGC**: "DFGC 2021: A DeepFake Game Competition." [Paper](https://arxiv.org/abs/2106.01217)    [Dowload](https://github.com/bomb2peng/DFGC_starterkit)
* **FFIW-10K**: "Face Forensics in the Wild." [Paper](https://arxiv.org/abs/2103.16076)    [Download](https://github.com/tfzhou/FFIW)
* **ForgeryNet**: "ForgeryNet: A Versatile Benchmark for Comprehensive Forgery Analysis." [Paper](https://arxiv.org/abs/2103.05630)    [Download](https://github.com/yinanhe/forgerynet)

|                     | Real Videos | Fake Videos |
| :-----------------: | :---------: | :---------: |
|        UADFV        |     49      |     49      |
|   Deepfake-TIMIT    |     320     |     640     |
|        DFFD         |    1000     |    3000     |
|    Celeb-DF (v2)    |     590     |    5639     |
|        DFDC         |   23,564    |   104,500   |
| DeeperForensics-1.0 |   50,000    |   10,000    |
|   FaceForensic++    |    1000     |    5000     |
|     ForgeryNet      |   99,630    |   121,617   |



### Image Datasets

* **DFFD**: "On the Detection of Digital Face Manipulation." [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Dang_On_the_Detection_of_Digital_Face_Manipulation_CVPR_2020_paper.pdf)    [Download](http://cvlab.cse.msu.edu/project-ffd.html)
* **FFHQ**: "A Style-Based Generator Architecture for Generative Adversarial Networks." [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Karras_A_Style-Based_Generator_Architecture_for_Generative_Adversarial_Networks_CVPR_2019_paper.pdf)    [Download](https://github.com/NVlabs/ffhq-dataset)
* **iFakeFaceDB**: "GANprintR: Improved Fakes and Evaluation of the State of the Art in Face Manipulation Detection." [Paper](https://arxiv.org/abs/1911.05351)    [Download](https://github.com/socialabubi/iFakeFaceDB)
* **100k Faces Generated by AI (Online)**: [Download](https://generated.photos/datasets)

|             | Real Images |    Fake Images     |
| :---------: | :---------: | :----------------: |
|    DFFD     |   58,703    |      240,336       |
|    FFHQ     |      -      | 70,000 (GAN-based) |
| iFakeFaceDB |      -      | 87,000 (StyleGAN)  |
| 100k Faces  |      -      | 100,000 (StyleGAN) |
| ForgeryNet  |  1,438,201  |     1,457,861      |



## Tools

* **Deepfakes-FaceSwap**: [Github](https://github.com/deepfakes/faceswap)
* **FaceSwap**: [Github](https://github.com/MarekKowalski/FaceSwap/)
* **dfaker**: [Github](https://github.com/dfaker/df)
* **FaceSwap-GAN**: [Github](https://github.com/shaoanlu/faceswap-GAN)
* **Face2Face**: [Github](https://github.com/datitran/face2face-demo)
* **DeepFaceLab**: [Github](https://github.com/iperov/DeepFaceLab)
* **DeepFaceLive**: [Github](https://github.com/iperov/DeepFaceLive)
* **FaceSwap Online**: [Website](https://faceswap.dev/)
* **MyVoiceYourFace**: [Website](https://myvoiceyourface.com/)
* **Online Deepfake Maker**: [Website](https://deepfakesweb.com/)
* **Online Deepfake Video Creator**: [Website](https://mmasked.com/)
* **Generated Photos**: [Website](https://generated.photos/)



## Papers

### CVPR

* "TediGAN: Text-Guided Diverse Face Image Generation and Manipulation", CVPR 2021: [Paper](https://arxiv.org/pdf/2012.03308v2.pdf)    [Github](https://github.com/IIGROUP/TediGAN)
* "One Shot Face Swapping on Megapixels", CVPR 2021: [Paper](https://arxiv.org/pdf/2105.04932v1.pdf)    [Github](https://github.com/zyainfal/One-Shot-Face-Swapping-on-Megapixels)
* "Face Forensics in the Wild", CVPR 2021: [Paper](https://arxiv.org/abs/2103.16076)    [Github](https://github.com/tfzhou/FFIW)
* "High-Fidelity and Arbitrary Face Editing", CVPR 2021: [Paper](https://arxiv.org/abs/2103.15814)

* "Celeb-DF: A Large-Scale Challenging Dataset for DeepFake Forensics", CVPR 2020: [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Celeb-DF_A_Large-Scale_Challenging_Dataset_for_DeepFake_Forensics_CVPR_2020_paper.html)    [Github](https://github.com/yuezunli/celeb-deepfakeforensics)
* "DeeperForensics-1.0: A Large-Scale Dataset for Real-World Face Forgery Detection", CVPR 2020: [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Jiang_DeeperForensics-1.0_A_Large-Scale_Dataset_for_Real-World_Face_Forgery_Detection_CVPR_2020_paper.html)       [Github](https://github.com/EndlessSora/DeeperForensics-1.0)
* "MaskGAN: Towards Diverse and Interactive Facial Image Manipulation", CVPR 2020: [Paper](https://ieeexplore.ieee.org/document/9157722/)    [Github](https://github.com/switchablenorms/CelebAMask-HQ)
* "Semantic Component Decomposition for Face Attribute Manipulation", CVPR 2019: [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Semantic_Component_Decomposition_for_Face_Attribute_Manipulation_CVPR_2019_paper.pdf)
* "A Style-Based Generator Architecture for Generative Adversarial Networks", CVPR 2019: [Paper](https://arxiv.org/abs/1812.04948)
* "StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation",CVPR 2018: [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Choi_StarGAN_Unified_Generative_CVPR_2018_paper.pdf)

### ICCV

* "A Latent Transformer for Disentangled Face Editing in Images and Videos", ICCV 2021: [Paper](https://arxiv.org/abs/2106.11895) [Github](https://github.com/InterDigitalInc/Latent-Transformer)
* "Diagonal Attention and Style-based GAN for Content-Style Disentanglement in
  Image Generation and Translation", ICCV 2021: [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Kwon_Diagonal_Attention_and_Style-Based_GAN_for_Content-Style_Disentanglement_in_Image_ICCV_2021_paper.pdf)
* "Dual Projection Generative Adversarial Networks for Conditional Image
  Generation", ICCV 2021: [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Han_Dual_Projection_Generative_Adversarial_Networks_for_Conditional_Image_Generation_ICCV_2021_paper.pdf)
* "LoFGAN: Fusing Local Representations for Few-shot Image Generation", ICCV 2021: [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Gu_LoFGAN_Fusing_Local_Representations_for_Few-Shot_Image_Generation_ICCV_2021_paper.pdf) [Github](https://github.com/edward3862/LoFGAN-pytorch)
* "Semi-Supervised Single-Stage Controllable GANs for Conditional Fine-Grained
  Image Generation": [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_Semi-Supervised_Single-Stage_Controllable_GANs_for_Conditional_Fine-Grained_Image_Generation_ICCV_2021_paper.pdf)
* "Unsupervised Image Generation with Infinite Generative Adversarial Networks", ICCV 2021: [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Ying_Unsupervised_Image_Generation_With_Infinite_Generative_Adversarial_Networks_ICCV_2021_paper.pdf) [Github](https://github.com/yinghdb/MICGANs)

* "Make a Face: Towards Arbitrary High Fidelity Face Manipulation", ICCV 2019: [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Qian_Make_a_Face_Towards_Arbitrary_High_Fidelity_Face_Manipulation_ICCV_2019_paper.pdf)
* "FSGAN: Subject Agnostic Face Swapping and Reenactment", ICCV 2019: [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Nirkin_FSGAN_Subject_Agnostic_Face_Swapping_and_Reenactment_ICCV_2019_paper.pdf)    [Github](https://github.com/YuvalNirkin/fsgan)
* "SC-FEGAN: Face Editing Generative Adversarial Network with User???s Sketch and Color", ICCV 2019: [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Jo_SC-FEGAN_Face_Editing_Generative_Adversarial_Network_With_Users_Sketch_and_ICCV_2019_paper.pdf)    [Github](https://github.com/run-youngjoo/SC-FEGAN)

### ECCV

* "Hierarchical Face Aging through Disentangled Latent Characteristics", ECCV 2020: [Paper](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480086.pdf)
* "CONFIG: Controllable Neural Face Image Generation", ECCV 2020: [Paper](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560290.pdf)
* "CAFE-GAN: Arbitrary Face Attribute Editing with Complementary Attention Feature", ECCV 2020: [paper](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590511.pdf)
* "High Resolution Zero-Shot Domain Adaptation of Synthetically Rendered Face Images", ECCV 2020: [Paper](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730222.pdf)

* "Attribute-Guided Face Generation Using Conditional CycleGAN",ECCV 2018: [Paper](http://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Yongyi_Lu_Attribute-Guided_Face_Generation_ECCV_2018_paper.pdf)
* "X2Face: A network for controlling face generation using images, audio, and pose codes", ECCV 2018: [Paper](http://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Olivia_Wiles_X2Face_A_network_ECCV_2018_paper.pdf)
* "Generative Adversarial Network with Spatial Attention for Face Attribute Editing", ECCV 2018: [Paper](http://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Gang_Zhang_Generative_Adversarial_Network_ECCV_2018_paper.pdf)
* "Semi-supervised Adversarial Learning to Generate Photorealistic Face Images of New Identities from 3D Morphable Model", ECCV 2018: [Paper](http://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Baris_Gecer_Semi-supervised_Adversarial_Learning_ECCV_2018_paper.pdf)    [Github](https://github.com/barisgecer/facegan)
* "ELEGANT: Exchanging Latent Encodings with GAN for Transferring Multiple Face Attributes", ECCV 2018: [Paper](http://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Taihong_Xiao_ELEGANT_Exchanging_Latent_ECCV_2018_paper.pdf)    [Github](https://github.com/Prinsphield/ELEGANT)
* "A Hybrid Model for Identity Obfuscation by Face Replacement", ECCV 2018: [Paper](http://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Qianru_Sun_A_Hybrid_Model_ECCV_2018_paper.pdf)

### ICLR

* "CCGAN: CONTINUOUS CONDITIONAL GENERATIVE ADVERSARIAL NETWORKS FOR IMAGE GENERATION", ICLR 2021: [Paper](https://openreview.net/pdf?id=PrzjugOsDeE)    [Github](https://github.com/UBCDingXin/improved_CcGAN)
* "FROM INFERENCE TO GENERATION: END-TO-END FULLY SELF-SUPERVISED GENERATION OF HUMAN FACE FROM SPEECH", ICLR 2020: [Paper](https://openreview.net/pdf?id=H1guaREYPr)
* "Progressive Growing of GANs for Improved Quality, Stability, and Variation", ICLR 2018: [Paper](https://arxiv.org/abs/1710.10196)    [Github](https://github.com/tkarras/progressive_growing_of_gans)

### IJCAI

* "Reference-guided Face Component Editing", IJCAI 2020: [Paper](https://arxiv.org/abs/2006.02051)
* "Talking Face Generation by Conditional Recurrent Adversarial Network", IJCAI 2019: [Paper](https://www.ijcai.org/Proceedings/2019/0129.pdf)    [Github](https://github.com/susanqq/Talking_Face_Generation)

### AAAI

* "GDFace: Gated Deformation for Multi-view Face Image Synthesis", AAAI 2020: [Paper](http://www.shengfenghe.com/qfy-content/uploads/2020/04/4aa081262dd1fafd6ffb9b95444dc39b.pdf)
* "CG-GAN: An Interactive Evolutionary GAN-based Approach for Facial Composite Generation", AAAI 2020: [Paper](https://pure.itu.dk/portal/files/85687312/1912.05020.pdf)

### ACM MM

* "DeepFacePencil: Creating Face Images from Freehand Sketches", ACM MM 2020: [Paper](https://dl.acm.org/doi/10.1145/3394171.3413684)
* "Talking Face Generation with Expression-Tailored Generative Adversarial Network", ACM MM 2020: [Paper](https://dl.acm.org/doi/10.1145/3394171.3413844)
* "SimSwap: An Efficient Framework For High Fidelity Face Swapping", ACM MM 2020: [Paper](https://dl.acm.org/doi/10.1145/3394171.3413630)
* "FakePolisher: Making DeepFakes More Detection-Evasive by Shallow Reconstruction", ACM MM 2020: [Paper](https://dl.acm.org/doi/10.1145/3394171.3413732)
* "Towards Automatic Face-to-Face Translation", ACM MM 2019: [Paper](https://arxiv.org/abs/2003.00418v1)    [Github](https://github.com/Rudrabha/LipGAN)
* "LinesToFacePhoto: Face Photo Generation From Lines With Conditional Self-Attention Generative Adversarial Networks", ACM MM 2019: [Paper](https://dl.acm.org/doi/10.1145/3343031.3350854)

### TPAMI

* "InterFaceGAN: Interpreting the Disentangled Face Representation Learned by GANs", TPAMI 2020: [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9241434)
