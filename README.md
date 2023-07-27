# awesome-video-segmentation
Awesome Video Segmentation: Recent progress in video segmentation. 

A list of recent papers on different types of video segmentation tasks.  









## Contents
> 0\. [Tasks and Datasets](#Tasks-and-Datasets)
>
> 1\. [Automatic Video Object Segmentation (AVOS)](#Automatic-Video-Object-Segmentation-(AVOS))
>
> 2\. [Semi Automatic Video Object Segmentation (SVOS)](#Semi-Automatic-Video-Object-Segmentation-(SVOS))
>
> 3\. [Interactive Video Object Segmentation (IVOS)](#)
>
> 4\. [Video Instance Segmentation (VIS)](#)
>
> 5\. [Actor-Action Segmentation](#)
>
> 6\. [Video Semantic Segmentation (VSS)](#)
>
> 7\. [Video Panoptic Segmentation (VPS)](#)
>
> 8\. [Depthaware Video Panoptic Segmentation (DVPS)](#)
>
> 9\. [Panoramic Video Panoptic Segmentation (PVPS)](#)
>
> 10\. [Text-referring Video Object Segmentation (RVOS)](#)
>
> 11\. [Audio-referring Video Object Segmentation](#)


## Tasks and Datasets

| Task Category               | Task                                                        | Target                                | Instances  | Tracking   | Datasets                                       |
|-----------------------------|-------------------------------------------------------------|---------------------------------------|------------|------------|------------------------------------------------|
|           Objects           | Automatic Video Object Segmentation (AVOS)                  | Primary moving object                 | -          | -          | DAVIS 2016, MoCA, YouTube-VOS, YouTube-Objects |
|                             | Semi-automatic VOS (SVOS)                                   | Mask-guided object                    | -          | -          | DAVIS'2017                                     |
|                             | Interactive VOS (IVOS)                                      | Scribble-guided object                | -          | -          | DAVIS'2017                                     |
|                             | Video Instance Segmentation (VIS)                           | All Objects                           | \checkmark | \checkmark | YouTube-VIS, OVIS                              |
|         Actor-action        | Actor-action segmentation                                   | Primary Object related to actions     | -          | -          | A2D                                            |
|             Scene           | Video Semantic Segmentation/ Video Scene Parsing (VSS/ VSP) | All thing and stuff classes           | -          | -          | VIPER, VSPW                                    |
|                             | Video Panoptic Segmentation (VPS)                           | All thing and stuff classes           | \checkmark | \checkmark | Cityscapes-VPS, VIPER, VIPSeg                  |
|                             | Depth-aware Video Panoptic Segmentation (DVPS)              | All thing and stuff classes and depth | \checkmark | \checkmark | Cityscapes-DVPS, SemanticKITTI-DVPS            |
|                             | Panoramic Video Panoptic Segmentation (PVPS)                | All thing and stuff classes           | \checkmark | \checkmark | WOD:PVPS                                       |
|            Multimodal       | Text guided VOS/Referring-VOS (RVOS)                        | Text reference guided object          | -          | -          | A2D-Sentence, RE-DAVIS, RVOS                   |
|                             | Audio Guided VOS (AGVOS)                                    | Audio reference guided object         | -          | -          | AVOS                                           |





## Automatic Video Object Segmentation (AVOS)
Automatic Video Object Segmentation (AVOS), often called primary object segmentation, is defined as grouping pixels into foreground object masks representing the primary object in a video sequence, where primary is distinguished as the object showing dominant motion or distinguishing appearances across the frames. For this reason, AVOS often has been termed foreground/background segmentation since an object with distinctive motion and/or appearance properties in a video sequence is generally the foreground object. Since no prior information is available, this kind of segmentation also is called unsupervised VOS or zero-shot VOS. In addition to the challenges common to most video segmentation task that were listed above, AVOS also faces the challenges of lack of prior information regarding the objects of interest. Some of the recent approaches to AVOS are listed below. 

- **[MED-VT]** MED-VT: Multiscale encoder-decoder video transformer with application to object segmentation. *CVPR 2023* [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Karim_MED-VT_Multiscale_Encoder-Decoder_Video_Transformer_With_Application_To_Object_Segmentation_CVPR_2023_paper.pdf) [Code](https://rkyuca.github.io/medvt/)
- **[PMN]** Unsupervised video object segmentation via prototype memory network. *WACV 2023*, [Paper](https://openaccess.thecvf.com/content/WACV2023/papers/Lee_Unsupervised_Video_Object_Segmentation_via_Prototype_Memory_Network_WACV_2023_paper.pdf)
- **[TMO]** Treating motion as option to reduce motion dependency in unsupervised video object segmentation. *WACV 2023*, [Paper](https://openaccess.thecvf.com/content/WACV2023/papers/Cho_Treating_Motion_as_Option_To_Reduce_Motion_Dependency_in_Unsupervised_WACV_2023_paper.pdf)
- **[HFAN]** Hierarchical feature alignment network for unsupervised video object segmentation. *ECCV 2022*, [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940584.pdf), [Code](https://github.com/NUST-Machine-Intelligence-Laboratory/HFAN)
- **[IMP]** Iteratively selecting an easy reference frame makes unsupervised video object segmentation easier. *AAAI 2022*, [Paper](https://arxiv.org/abs/2112.12402)
- **[COSNet]** See more,know more: Unsupervised video object segmentation with co-attention Siamese networks. *CVPR 2019*, [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lu_See_More_Know_More_Unsupervised_Video_Object_Segmentation_With_Co-Attention_CVPR_2019_paper.pdf), [Code](https://github.com/carrierlxk/COSNet)
- **[RTNet]** Reciprocal transformations for unsupervised video object segmentation. *CVPR 2021*, [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Ren_Reciprocal_Transformations_for_Unsupervised_Video_Object_Segmentation_CVPR_2021_paper.pdf), [Code](https://github.com/OliverRensu/RTNet)
- **[MATNet]** Motionattentive transition for zero-shot video object segmentation. *AAAI 2020*, [Paper](https://arxiv.org/pdf/2003.04253.pdf), [Code](https://github.com/tfzhou/MATNet)

## Semi Automatic Video Object Segmentation (SVOS)



  

