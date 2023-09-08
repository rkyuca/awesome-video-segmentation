# awesome-video-segmentation
Awesome Video Segmentation: Recent progress in video segmentation. 

A list of recent papers on different types of video segmentation tasks.  









## Contents
> 0\. [Tasks and Datasets](#Tasks-and-Datasets)
>
> 1\. [Automatic Video Object Segmentation](#Automatic-Video-Object-Segmentation)
>
> 2\. [Semi Automatic Video Object Segmentation](#Semi-Automatic-Video-Object-Segmentation)
>
> 3\. [Interactive Video Object Segmentation](#Interactive-Video-Object-Segmentation)
>
> 4\. [Video Instance Segmentation](#Video-Instance-Segmentation)
>
> 5\. [Actor Action Segmentation](#[Actor-Action-Segmentation)
>
> 6\. [Video Semantic Segmentation](#Video-Semantic-Segmentation)
>
> 7\. [Video Panoptic Segmentation](#Video-Panoptic-Segmentation)
>
> 8\. [Depth Aware Video Panoptic Segmentation](#Depth-Aware-Video-Panoptic-Segmentation)
>
> 9\. [Panoramic Video Panoptic Segmentation](#Panoramic-Video-Panoptic-Segmentation)
>
> 10\. [Text Referring Video Object Segmentation](#Text-Referring-Video-Object-Segmentation)
>
> 11\. [Audio Referring Video Object Segmentation](#Audio-Referring-Video-Object-Segmentation)


## Tasks and Datasets

| Task Category               | Task                                                        | Target                                | Instances          | Tracking           | Datasets                                       |
|-----------------------------|-------------------------------------------------------------|---------------------------------------|--------------------|--------------------|------------------------------------------------|
|           Objects           | Automatic Video Object Segmentation (AVOS)                  | Primary moving object                 | -                  | -                  | DAVIS 2016, MoCA, YouTube-VOS, YouTube-Objects |
|                             | Semi-automatic VOS (SVOS)                                   | Mask-guided object                    | -                  | -                  | DAVIS'2017                                     |
|                             | Interactive VOS (IVOS)                                      | Scribble-guided object                | -                  | -                  | DAVIS'2017                                     |
|                             | Video Instance Segmentation (VIS)                           | All Objects                           | :heavy_check_mark: | :heavy_check_mark: | YouTube-VIS, OVIS                              |
|         Actor-action        | Actor-action segmentation                                   | Primary Object related to actions     | -                  | -                  | A2D                                            |
|             Scene           | Video Semantic Segmentation/ Video Scene Parsing (VSS/ VSP) | All thing and stuff classes           | -                  | -                  | VIPER, VSPW                                    |
|                             | Video Panoptic Segmentation (VPS)                           | All thing and stuff classes           | :heavy_check_mark: | :heavy_check_mark: | Cityscapes-VPS, VIPER, VIPSeg                  |
|                             | Depth-aware Video Panoptic Segmentation (DVPS)              | All thing and stuff classes and depth | :heavy_check_mark: | :heavy_check_mark: | Cityscapes-DVPS, SemanticKITTI-DVPS            |
|                             | Panoramic Video Panoptic Segmentation (PVPS)                | All thing and stuff classes           | :heavy_check_mark: | :heavy_check_mark: | WOD:PVPS                                       |
|            Multimodal       | Text Referring VOS/Referring-VOS (RVOS)                     | Text reference guided object          | -                  | -                  | A2D-Sentence, RE-DAVIS, RVOS                   |
|                             | Audio Referring VOS (ARVOS)                                 | Audio reference guided object         | -                  | -                  | AVOS                                           |





## Automatic Video Object Segmentation

- **[MED-VT]** MED-VT: Multiscale encoder-decoder video transformer with application to object segmentation. *CVPR 2023*, [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Karim_MED-VT_Multiscale_Encoder-Decoder_Video_Transformer_With_Application_To_Object_Segmentation_CVPR_2023_paper.pdf) [Code](https://rkyuca.github.io/medvt/)
- **[PMN]** Unsupervised video object segmentation via prototype memory network. *WACV 2023*, [Paper](https://openaccess.thecvf.com/content/WACV2023/papers/Lee_Unsupervised_Video_Object_Segmentation_via_Prototype_Memory_Network_WACV_2023_paper.pdf)
- **[TMO]** Treating motion as option to reduce motion dependency in unsupervised video object segmentation. *WACV 2023*, [Paper](https://openaccess.thecvf.com/content/WACV2023/papers/Cho_Treating_Motion_as_Option_To_Reduce_Motion_Dependency_in_Unsupervised_WACV_2023_paper.pdf)
- **[HFAN]** Hierarchical feature alignment network for unsupervised video object segmentation. *ECCV 2022*, [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940584.pdf), [Code](https://github.com/NUST-Machine-Intelligence-Laboratory/HFAN)
- **[IMP]** Iteratively selecting an easy reference frame makes unsupervised video object segmentation easier. *AAAI 2022*, [Paper](https://arxiv.org/abs/2112.12402)
- **[RTNet]** Reciprocal transformations for unsupervised video object segmentation. *CVPR 2021*, [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Ren_Reciprocal_Transformations_for_Unsupervised_Video_Object_Segmentation_CVPR_2021_paper.pdf), [Code](https://github.com/OliverRensu/RTNet)
- **[MATNet]** Motionattentive transition for zero-shot video object segmentation. *AAAI 2020*, [Paper](https://arxiv.org/pdf/2003.04253.pdf), [Code](https://github.com/tfzhou/MATNet)
- **[COSNet]** See more,know more: Unsupervised video object segmentation with co-attention Siamese networks. *CVPR 2019*, [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lu_See_More_Know_More_Unsupervised_Video_Object_Segmentation_With_Co-Attention_CVPR_2019_paper.pdf), [Code](https://github.com/carrierlxk/COSNet)



## Semi Automatic Video Object Segmentation

- **[PCVOS]**  Per-clip video object segmentation. *CVPR 2022*, [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Park_Per-Clip_Video_Object_Segmentation_CVPR_2022_paper.pdf), [Code](https://github.com/pkyong95/PCVOS) 
- **[AOT]** Associating objects with transformers for video object segmentation. *NeurIPS 2021*, [Paper](https://openreview.net/pdf?id=hl3v8io3ZYt)
- **[CFBI+]** Collaborative video object segmentation by multiscale foreground-background integration. *PAMI 2021*, [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9435058), [Code](https://github.com/z-x-yang/CFBI)
- **[SST]**  SSTVOS: Sparse spatiotemporal transformers for video object segmentation. *CVPR 2021*, [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Duke_SSTVOS_Sparse_Spatiotemporal_Transformers_for_Video_Object_Segmentation_CVPR_2021_paper.pdf), [Code](https://github.com/dukebw/SSTVOS)
- **[STCN]** Rethinking space-time networks with improved memory coverage for efficient video object segmentation. *NeurIPS 2021*, [Paper](https://openreview.net/pdf?id=vllRjSTWcLs), [Code](https://github.com/hkchengrex/STCN)
- **[HMMN]** Hierarchical memory matching network for video object segmentation. *ICCV 2021*, [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Seong_Hierarchical_Memory_Matching_Network_for_Video_Object_Segmentation_ICCV_2021_paper.pdf), [Code](https://github.com/Hongje/HMMN)
- **[KMN]** Kernelized memory network for video object segmentation. *ECCV 2020*, [Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670630.pdf)

## Interactive Video Object Segmentation  


- **[MiVOS]** Modular interactive video object segmentation: Interaction-to-mask, propagation and difference-aware fusion. *CVPR 2021*, [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Cheng_Modular_Interactive_Video_Object_Segmentation_Interaction-to-Mask_Propagation_and_Difference-Aware_Fusion_CVPR_2021_paper.pdf), [Code](https://github.com/hkchengrex/MiVOS) 
- **[GIS]**  Guided interactive video object segmentation using reliability-based attention maps. *CVPR 2021*, [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Heo_Guided_Interactive_Video_Object_Segmentation_Using_Reliability-Based_Attention_Maps_CVPR_2021_paper.pdf), [Code](https://github.com/yuk6heo/GIS-RAmap)
- **[ATNet]** Interactive video object segmentation using global and local transfer modules. *ECCV 2020*, [Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620290.pdf), [Code](https://github.com/yuk6heo/IVOS-ATNet)
- **[MANet]** Memory aggregation networks for efficient interactive video object segmentation. *CVPR 2020*, [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Miao_Memory_Aggregation_Networks_for_Efficient_Interactive_Video_Object_Segmentation_CVPR_2020_paper.pdf), [Code](https://github.com/lightas/CVPR2020_MANet)
- **[IPNet]** Fast user-guided video object segmentation by interaction-and-propagation networks. *CVPR 2019*, [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Oh_Fast_User-Guided_Video_Object_Segmentation_by_Interaction-And-Propagation_Networks_CVPR_2019_paper.pdf), [Code](https://github.com/seoungwugoh/ivs-demo)


## Video Instance Segmentation


| Methods             | Transformer-based  | YouTube-VIS-2019   | YouTube-VIS-2021 | OVIS     | UVO      |
|---------------------|--------------------|--------------------|------------------|----------|----------|
| CrossVIS            |       \-           |   36.6             |  34.2            | 14.9     | \-       |
| VisTR               |                    |   40.1             | \-               | \-       | \-       |
| IFC                 |                    |   42.6             | 35.2             | \-       | \-       |
| Seq Mask R-CNN      |              \-    |   47.6             | \-               | \-       | \-       |
| EfficientVIS        |                    |   39.8             | \-               | \-       | \-       |
| TeViT               |                    |   46.6             | 37.9             | 17.4     | \-       |
| SeqFormer           |                    |   59.3             | \-               | \-       | \-       |
| TubeFormer-DeepLab  |                    |   47.5             | 41.2             | \-       | \-       |
| Video K-Net         |                    |   51.4             | \-               | \-       | \-       |
| FreeSOLO            |          \-        |     \-             | \-               | \-       | 4.8      |
| IDOL                |                    |    62.2            | 56.1             | 42.6     | \-       |
| VMT                 |                    |    59.7            | \-               | 19.8     | \-       |
| MS-STS VIS          |                    |    61.0            | \-               | \-       | \-       |
| InstMove            |                    |     \-             | \-               | 30.7     | \-       |
| GenVIS              |                    |   **64.0**         | **59.6**         | **45.4** | \-       |
| CAROQ               |                    |     61.4           | 54.5             | 38.2     | \-       |
| CutLER              |                    |       \-           | \-               | \-       | **10.1** |


- **[CutLER]** Cut and learn for unsupervised object detection and instance segmentation. *CVPR 2023*, [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Cut_and_Learn_for_Unsupervised_Object_Detection_and_Instance_Segmentation_CVPR_2023_paper.pdf), [Code](https://github.com/facebookresearch/CutLER)
- **[CAROQ]** Context-aware relative object queries to unify video instance and panoptic segmentation. *CVPR 2023*, [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Choudhuri_Context-Aware_Relative_Object_Queries_To_Unify_Video_Instance_and_Panoptic_CVPR_2023_paper.pdf), [Code](https://github.com/AnwesaChoudhuri/CAROQ)
- **[GenVIS]** A generalized framework for video instance segmentation. *CVPR 2023*, [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Heo_A_Generalized_Framework_for_Video_Instance_Segmentation_CVPR_2023_paper.pdf), [Code](https://github.com/miranheo/GenVIS)
- **[InstMove]** InstMove: Instance motion for object-centric video segmentation. *CVPR 2023*, [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_InstMove_Instance_Motion_for_Object-Centric_Video_Segmentation_CVPR_2023_paper.pdf), [Code](https://github.com/wjf5203/VNext)
- **[MS-STS VIS]** Video instance segmentation via multi-scale spatio-temporal split attention transformer. *ECCV 2022*, [Paper](https://arxiv.org/pdf/2203.13253.pdf), [Code](https://github.com/OmkarThawakar/MSSTS-VIS)
- **[VMT]** Video mask transfiner for high-quality video instance segmentation. *ECCV 2022*, [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136880721.pdf), [Code](https://github.com/SysCV/vmt)
- **[IDOL]** In defense of online models for video instance segmentation. *ECCV 2022*, [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136880582.pdf), [Code](https://github.com/wjf5203/VNext)
- **[FreeSOLO ]** FreeSOLO: Learning to segment objects without annotations. *CVPR 2022*, [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_FreeSOLO_Learning_To_Segment_Objects_Without_Annotations_CVPR_2022_paper.pdf), [Code](https://github.com/NVlabs/FreeSOLO)
- **[Video K-Net]** Video K-Net: A simple, strong, and unified baseline for video segmentation. *CVPR 2022*, [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Video_K-Net_A_Simple_Strong_and_Unified_Baseline_for_Video_CVPR_2022_paper.pdf), [Code](https://github.com/lxtGH/Video-K-Net)
- **[TubeFormer-DeepLab]** TubeFormer-DeepLab: Video mask transformer. *CVPR 2022*, [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Kim_TubeFormer-DeepLab_Video_Mask_Transformer_CVPR_2022_paper.pdf), [Code]() 
- **[SeqFormer]** SeqFormer: Sequential transformer for video instance segmentation. *ECCV 2022*, [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136880547.pdf), [Code](https://github.com/wjf5203/SeqFormer) 
- **[TeViT]** Temporally efficient vision transformer for video instance segmentation. *CVPR 2022*, [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Temporally_Efficient_Vision_Transformer_for_Video_Instance_Segmentation_CVPR_2022_paper.pdf), [Code](https://github.com/hustvl/TeViT)
- **[EfficientVIS]** Efficient video instance segmentation via tracklet query and proposal. *CVPR 2022*, [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_Efficient_Video_Instance_Segmentation_via_Tracklet_Query_and_Proposal_CVPR_2022_paper.pdf), [Code]()
- **[Seq Mask R-CNN]** Video instance segmentation with a propose-reduce paradigm. *ICCV 2021*, [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Lin_Video_Instance_Segmentation_With_a_Propose-Reduce_Paradigm_ICCV_2021_paper.pdf), [Code](https://github.com/dvlab-research/ProposeReduce)
- **[IFC]** Video instance segmentation using inter-frame communication transformers. *NeurIPS 2021*, [Paper](https://proceedings.neurips.cc/paper/2021/file/6f2688a5fce7d48c8d19762b88c32c3b-Paper.pdf), [Code](https://github.com/sukjunhwang/IFC)
- **[VisTR]**  End-to-end video instance segmentation with transformers. *CVPR 2021*, [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_End-to-End_Video_Instance_Segmentation_With_Transformers_CVPR_2021_paper.pdf), [Code](https://github.com/Epiphqny/VisTR)
- **[CrossVIS]** Crossover learning for fast online video instance segmentation. *ICCV 2021*, [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Crossover_Learning_for_Fast_Online_Video_Instance_Segmentation_ICCV_2021_paper.pdf), [Code](https://github.com/hustvl/CrossVIS) 


## Actor Action Segmentation
 | Methods     | Transformer-based | A2D      |
 |-------------|-------------------|----------|
 | Ji et al.   | -                 | 36.9     |   
 | Dang et al. | -                 | 38.6     |  
 | SSA2D       | -                 | 39.5     | 
 | MED-VT      |                   | **52.6** |


- **[MED-VT]** MED-VT: Multiscale encoder-decoder video transformer with application to object segmentation. *CVPR 2023*, [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Karim_MED-VT_Multiscale_Encoder-Decoder_Video_Transformer_With_Application_To_Object_Segmentation_CVPR_2023_paper.pdf) [Code](https://rkyuca.github.io/medvt/)
- **[SSA2D]** We don’t need thousand proposals: Single shot actor action detection in videos. *WACV 2021 *, [Paper](https://openaccess.thecvf.com/content/WACV2021/papers/Rana_We_Dont_Need_Thousand_Proposals_Single_Shot_Actor-Action_Detection_in_WACV_2021_paper.pdf), [Code](https://github.com/aayushjr/ssa2d)
- **[Dang et al.]** Actor-action semantic segmentation with region masks. *BMVC 2018*, [Paper](https://arxiv.org/pdf/1807.08430.pdf), [Code]()
- **[Ji et al.]** End-to-end joint semantic segmentation of actors and actions in video. *ECCV 2018 *, [Paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Jingwei_Ji_End-to-End_Joint_Semantic_ECCV_2018_paper.pdf), [Code](https://github.com/JingweiJ/JointActorActionSeg)

## Video Semantic Segmentation
- **[]** . * *, [Paper](), [Code]()


## Video Panoptic Segmentation



## Depth Aware Video Panoptic Segmentation



## Panoramic Video Panoptic Segmentation



## Text Referring Video Object Segmentation



## Audio Referring Video Object Segmentation
