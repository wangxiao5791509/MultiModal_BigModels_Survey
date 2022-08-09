* **The summary of mainstream multi-modal pre-trained big models.** 



### Year 2022 

* Li, Juncheng, et al. "**Fine-Grained Semantically Aligned Vision-Language Pre-Training**." arXiv preprint arXiv:2208.02515 (2022). [[Paper](https://arxiv.org/pdf/2208.02515.pdf)]

* **GRIT-VLP: Grouped Mini-batch Sampling for Efficient Vision and Language Pre-training**, Jaeseok Byun, Taebaek Hwang, Jianlong Fu, and Taesup Moon, arXiv:2208.04060 
[[Paper](https://arxiv.org/pdf/2208.04060.pdf)]
[[Code](https://github.com/jaeseokbyun/GRIT-VLP)]

* Wang, Tengfei, et al. "**Pretraining is All You Need for Image-to-Image Translation**." arXiv preprint arXiv:2205.12952 (2022). [[Paper](https://arxiv.org/pdf/2205.12952.pdf)] [[Code](https://tengfei-wang.github.io/PITI/index.html)]

* Wang, Jinpeng, et al. "**Object-aware Video-language Pre-training for Retrieval.**" Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022. 
[[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Object-Aware_Video-Language_Pre-Training_for_Retrieval_CVPR_2022_paper.pdf)] 
[[Code](https://github.com/FingerRec/OA-Transformer)]

* **See Finer, See More: Implicit Modality Alignment for Text-based Person Retrieval**, Xiujun Shu, Wei Wen, Haoqian Wu, Keyu Chen, Yiran Song, Ruizhi Qiao, Bo Ren, Xiao Wang, The 2nd Workshop on Real-World Surveillance: Applications and Challenges, ECCVW-2022  
[[Paper]()] 
[[Code](https://github.com/shuxjweb/IVT)]

* **Learning Visual Representation from Modality-Shared Contrastive Language-Image Pre-training**, 2022 European Conference on Computer Vision (ECCV 2022), Haoxuan You*, Luowei Zhou*, Bin Xiao*, Noel Codella*, Yu Cheng, Ruochen Xu, Shih-Fu Chang, Lu Yuan. 
[[Paper](https://arxiv.org/pdf/2207.12661.pdf)]
[[Code](https://github.com/Hxyou/MSCLIP)]

* Zhao, Tiancheng, et al. "**VL-CheckList: Evaluating Pre-trained Vision-Language Models with Objects, Attributes and Relations.**" arXiv preprint arXiv:2207.00221 (2022). [[Paper](https://arxiv.org/pdf/2207.00221.pdf)] [[Code](https://github.com/om-ai-lab/VL-CheckList)]

* **DemoVLP: Revitalize Region Feature for Democratizing Video-Language Pre-training**, Guanyu Cai, Yixiao Ge, Alex Jinpeng Wang, Rui Yan, Xudong Lin, Ying Shan, Lianghua He, Xiaohu Qie, Jianping Wu, Mike Zheng Shou
[[Paper](https://arxiv.org/abs/2203.07720)]
[[Code](https://github.com/showlab/DemoVLP)]

* Yan, Rui, et al. "**Video-Text Pre-training with Learned Regions.**" arXiv preprint arXiv:2112.01194 (2021).
[[Paper]](https://arxiv.org/pdf/2112.01194.pdf)] 
[[Code](https://github.com/showlab/Region_Learner)]

* Wang, Alex Jinpeng, et al. "**All in one: Exploring unified video-language pre-training.**" arXiv preprint arXiv:2203.07303 (2022).
[[Paper](https://arxiv.org/pdf/2203.07303.pdf)]
[[Code](https://github.com/showlab/all-in-one)]

* **Egocentric Video-Language Pretraining**, Kevin Qinghong Lin and Alex Jinpeng Wang and Mattia Soldan and Michael Wray and Rui Yan and Eric Zhongcong Xu and Difei Gao and Rongcheng Tu and Wenzhe Zhao and Weijie Kong and Chengfei Cai and Hongfa Wang and Dima Damen and Bernard Ghanem and Wei Liu and Mike Zheng Shou, arXiv-2022 
[[Paper](https://arxiv.org/pdf/2206.01670.pdf)]
[[Code](https://github.com/showlab/EgoVLP)]

* **LocVTP: Video-Text Pre-training for Temporal Localization** (ECCV 2022), Meng Cao, Tianyu Yang, Junwu Weng, Can Zhang, Jue Wang and Yuexian Zou.  
[[Paper](https://arxiv.org/pdf/2207.10362.pdf)] 
[[Code](https://github.com/mengcaopku/LocVTP)]

* Gui L, Wang B, Huang Q, et al. **Kat: A knowledge augmented transformer for vision-and-language**[J]. arXiv preprint arXiv:2112.08614, 2021. 
[[**Paper**](https://arxiv.org/pdf/2112.08614.pdf)]
[[**Code**](https://github.com/guilk/KAT)] 



|**NO.**     | **Model**     | **Publish**        | **Modality**        | **Architecture**   | **Objective**     |**Highlights**   |**Code**         |
|:-----------|:-----------   |:----------------   |:----------------    |:----------------   |:----------------  |:----------------|:----------------|
|64 |pyramidCLIP |arXiv-2022  |image-text |CNN+Trans |CS|Hierarchical image-text contrastive learning|- 
|65 |VLC|arXiv-2022 |image-text  |ViT  |MIM, MLM ITM|Built on top of MAE that does not require trained on ImageNet|[[Code](https://github.com/guilk/VLC)]  
|66 |VLCDoC|arXiv-2022 |image-text  |Trans  |CS |Contrastive Pre-Training for document classification |-  
|67 |MVP |arXiv-2022  |image-text  |ViT  |MIM|Multimodality-guided visual pre-training leads to impressive gains |- 
|68 |COTS |arXiv-2022 |image-text  |Trans  |CS, KLD, MVLM|Token- and task-level interaction are proposed to enhance cross-modal interaction |-  
|69 |Flamingo |arXiv-2022 |image-text  |NFNet  |CS  |An architecture for accepting arbitrarily interleaved visual data and text as input |[[Code](https://github.com/lucidrains/flamingo-pytorch)]  
|70 |BLIP |arXiv-2022 |image-text |BERT  |CS, MML, MLM  |Propose the multimodal mixture of encoder-decoder, and captioning-filtering scheme |[[Code](https://github.com/salesforce/BLIP)]  
|71 |TCL |CVPR-2022 |image-text  |BERT  |CMA, IMC, LMI ITM, MLM  |The first work considers local structure information for multi-modality representation learning |[[Code](https://github.com/uta-smile/TCL)]  
|72 |SCALE |CVPR-2022 |image, text, table video, audio  |BERT  |MRP, MLM, MEM MFP, MFP, MAM|A unified model to handle five modalities  |[[Code](https://xiaodongsuper.github.io/M5Product_dataset/)]  
|73 |Clinical-BERT |AAAI-2022 |image-text  |BERT  |CD, MMM MLM, IMM  |The first work to learn domain knowledge during pre-training for the medical domain |- 
|74 |ProbES |ACL-2022 |image-text  |LSTM, ViLBERT  |Ranking loss |Prompt-based learning for VLN based on CLIP |[[Code](https://github.com/liangcici/Probes-VLN)]   
|75 |VLP-MABSA |ACL-2022 |image-text |BERT |MLM, AOE, MRM AOG, MSP |Task-specific VL-PTMs for multimodal aspect-based sentiment analysis |[[Code](https://github.com/NUSTM/VLP-MABSA )]
|76 |R2D2 |arXiv-2022 |image-text |ViT, BERT |GCPR, FGR, MLM |A two-way distillation strategy is proposed, i.e., target- and feature-guided distillation |- 
|77 |DeFILIP|arXiv-2022 |image-text |ViT, ResNet |CS |A benchmark for CLIP and its variants |[[Code](https://github.com/Sense-GVT/DeCLIP)]  
|78 |CoCa |arXiv-2022 |image-text |Trans |CS, ITG |Jointly pre-train image text model with contrastive loss and captioning loss |- 
|79 |HiVLP |arXiv-2022 |image-text |Trans |LRM, HRL, VLM |Accelerate image-text retrieval via hierarchical retrieval |- 
|80 |CLIP-Event |CVPR-2022 |image-text |Trans |CS |Consider event structural knowledge and prompts in the pre-training phase.|[[Code](https://github.com/limanling/clip-event)] 
|81 |AudioCLIP |ICASSP-2022 |image-text-audio |Trans |CS |Build a triplet modality based PTMs like CLIP |[[Code](https://github.com/AndreyGuzhov/AudioCLIP)] 
|82 |VL-BEiT |arXiv-2022 |image-text |Trans |MLM, MIM, MVLM |Pretrain on both monomodal and multimodal data using a shared Transformer |[[Code](https://github.com/microsoft/unilm)] 
|83 |MV-GPT |arXiv-2022 |image-text |BERT |MLM, LG |Pre-train both a multi-modal video encoder and a sentence decoder jointly. |- 
|84 |MMKD |arXiv-2022 |image-text |BERT |ITM |Iteratively execute knowledge discovery and model pre-training for continuous learning |-
|85 |GLIPv2 |arXiv-2022 |image-text |Swin, BERT |PGL, CS, MLM |Serves both the localization and understanding tasks. |[[Code](https://github.com/microsoft/GLIP)]
|86 |LIMoE |arXiv-2022 |image-text |Trans |CS |multi-modal pre-training with a sparse mixture of experts model |- 
|87 |VLMixer |arXiv-2022 |image-text |Trans |MLM, CMCL, MTM |Implicit cross-modal alignment learning in unpaired VLP. |[[Code](https://github.com/ttengwang/VLMixer)]
|88 |ProtoCLIP |arXiv-2022 |image-text |Trans |CS |Combine the CLIP loss and prototypical supervisions for VLP. |[[Code](https://github.com/megvii-research/protoclip)] 
|89 |i-Code |arXiv-2022 |image-text-audio |Trans |MLM, MVM MSM, CS |It can handle different combinations of modalities (such as single-, dual-, and triple-modality) into a single representation space. |- 





















### Year 2021 
|**NO.**     | **Model**     | **Publish**        | **Modality**        | **Architecture**   | **Objective**     |**Highlights**   |**Code**         |
|:-----------|:-----------   |:----------------   |:----------------    |:----------------   |:----------------  |:----------------|:----------------|
|25 |XGPT |NLPCC-2021 |image-text |Trans |IC, MLM, IDA, MOR |Novel IDA pre-training; Share parameters between encoder and decoder |- 
|26 |ERNIE-ViL |AAAI-2021 |image-text |Trans |MOC, AttP, RelP, MLM, MOR, MML |Use the knowledge obtained from scene graph |[[Code](https://github.com/Muennighoff/vilio)] 
|27 |KVL-BERT |KBS-2021 |image-text |BERT |MOC, MLM |Integrate commonsense knowledge for visual commonsense reasoning |- 
|28 |VinVL |CVPR-2021 |image-text |Trans |MTL, 3-way CS |Verifying that visual feature matters in VLP, i.e., strong object detector brings better results |[[Code](https://github.com/pzzhang/VinVL)] 
|29 |VL-T5 |ICML-2021 |image-text |Trans |MLM, VQA, MML, VG, GC |Unified framework for VL via generating texts |[[Code](https://github.com/j-min/VL-T5)] 
|30 |ViLT |ICML-2021 |image-text |Trans |MLM, MML |Use linear embedding only for Fast VL transformer|[[Code](https://github.com/dandelin/vilt)] 
|31 |ALIGN |ICML-2021 |image-text |EfficientNet, BERT |CS |Milestone for image-text pre-training using noisy data  |- 
|32 |Kaleido-BERT |CVPR-2021 |image-text |Trans |MLM, MML, AKPM |Use saliency detector to generate multi-grained patches |[[Code](http://dpfan.net/Kaleido-BERT)] 
|33 |MDETR |ICCV-2021 |image-text |CNN+Trans |STP, MML |An end-to-end text-modulated detection system |[[Code](https://github.com/ashkamath/mdetr)] 
|34 |SOHO |CVPR-2021 |image-text |CNN+Trans |MLM, MOR, MML|Use a dynamic-updated visual dictionary for vision-language alignment |[[Code](https://github.com/researchmm/soho)] 
|35 |E2E-VLP |ACL-2021 |image-text |Trans |OBD, ITG |The first end-to-end pre-trained model for V+L understanding and generation |- 
|36 |PIM |NeurIPS-2021  |image-text |Trans |MLM, MML, MOR |Propose a inter-modality flow metric to measure and reveal vision and language fusion |- 
|37 |CLIP-ViL |arXiv-2021 |image-text |Trans |MLM, VQA, MML |Take the CLIP visual encoder as its visual backbone |[[Code](https://github.com/clip-vil/CLIP-ViL)] 
|38 |ALBEF |NeurIPS-2021 |image-text |Trans |CS, GR |Design a momentum model to address noisy data |[[Code](https://github.com/salesforce/ALBEF)]	 
|39 |SimVLM |arXiv-2021 |image-text |Trans |PrefixLM |Simple VL model using single PrefixLM pre-training objective only |- 
|40 |MURAL |arXiv-2021 |image-text |Trans |CS |Adopt multi-task contrastive learning objective (image-text, text-text) |- 
|41 |VLMo |arXiv-2021 |image-text |Trans |MLM, MML, CS |Jointly learns visual-, text-encoder and a fusion encoder |[[Code](https://aka.ms/vlmo)] 
|42 |METER  |CVPR-2022  |image-text  |Trans  |MLM, MOR, MOC, MML |An empirical study on VLP  |[[Code](https://github.com/zdou0830/METER)] 
|43 |CLIP  |ICML-2021 |image-text  |Resnet, Trans |CS  |Milestone for image-text pre-training using noisy data |[[Code](https://github.com/OpenAI/CLIP)] 
|44 |Frozen  |ICCV-2021 |video/image-text  |Trans  |MML  |Flexibly trained on both images and videos with captions jointly  |[[Code](https://github.com/m-bain/frozen-in-time)]  
|45 |RegionLearner  |arXiv-2021 |video-text  |Trans  |MML  |Implicitly learning object region without position supervision  |[[Code](https://github.com/showlab/Region_Learner)]  
|46 |DALL-E |ICML-2021  |image-text  |Trans  |ELB  |Achieve high quality image generation without using any of the training labels  |[[Code](https://github.com/openai/DALL-E)]  
|47 |BriVL |arXiv-2021  |image-text  |Trans  |InfoNCE  |First large-scale Chinese multi-modal pre-training model |[[Code](https://github.com/chuhaojin/WenLan-api-document)]  
|48 |M6 |arXiv-2021 |image-text  |Trans  |LM  |The largest pretrained model in Chinese |- 
|49 |CogView |NeurIPS-2021  |image-text  |Trans  |NLL|The first open-source large text-to-image transformer  |[[Code](https://github.com/THUDM/CogView)]  
|50 |VATT |NeurIPS-2021  |Video, Audio, Text  |Trans  |NCE, MIL-NCE |Modality-specific or Modality-agnostic triplet modality pre-trained model |[[Code](https://github.com/google-research/google-research/tree/master/vatt)]  
|51 |OPT |arXiv-2021 |image, Audio, Text  |Trans  |MLM, MVM, MoLM MAM, DTR, DIR  |The first pre-trained model that connects the three modalities of text, vision, and audio  |-  
|52 |Florence |arXiv-2021 |image-text  |CoSwin  |UniCL|Expand the representations from coarse-to-fine, static-to-dynamic, and RGB-to-MM |-  
|53 |ROSITA |MM-2021 |image-text  |Trans  |SKM, MLM, MRM |Incorporates both cross- and intra-modal knowledge, and proposed SKM strategy  |-  
|54 |GilBERT |IR-2021 |image-text  |BERT  |MLM, MOR  |Employ image-to-text captioning and text-to-image synthesizing in VLP |-  
|55 |U-VisualBERT |NAACL-2021  |image-text |Trans, BERT  |GR, MML  |\emph{Unpaired image-text data for pre-training |[[Code](https://github.com/uclanlp/visualbert)]  
|56 |M3P |CVPR-2021 |image-text  |BERT  |xMLM, MC-MLM, MC-MRM  |Multitask, Multilingual, Multimodal Pre-training |[[Code](https://github.com/microsoft/M3P)] 
|57 |NUWA |arXiv-2021 |image-text  |Trans  |T2I, T2V, V2V  |A 3D transformer framework can handle image, text, and video, simultaneously |[[Code](https://github.com/microsoft/NUWA)]  
|58 |GLIP |CVPR-2022 |image-text  |BERT  |CS|Unifying detection and grounding by reformulating object detection as phrase grounding |[[Code](https://github.com/microsoft/GLIP)]  
|59 |RegionCLIP |CVPR-2022 |image-text  |Trans  |Distillation loss, CS  |Learn region-level visual representations based on CLIP  |[[Code](https://github.com/microsoft/RegionCLIP)]  
|60 |DeCLIP |ICLR-2022 |image-text |ViT |InfoNCE, SS MVS, NNS |Learn generic visual features in a data efficient way |[[Code](https://github.com/Sense-GVT/DeCLIP)] 
|61 |SLIP |arXiv-2021 |image-text |ViT |CS, InfoNCE|Combine the self-supervised learning and CLIP pre-training in a multi-task framework |[[Code](https://github.com/facebookresearch/SLIP)] 
|62 |FILIP |arXiv-2021 |image-text |ViT |CS|Achieve finer-level alignment using the cross-modal late interaction scheme |- 
|63 |SemVLP |arXiv-2021 |image-text |Trans |MLM, MOP, ITM, QA |Fuse the single- and two-stream architectures |- 






### Year 2020 
|**NO.**     | **Model**     | **Publish**        | **Modality**        | **Architecture**   | **Objective**     |**Highlights**   |**Code**         |
|:-----------|:-----------   |:----------------   |:----------------    |:----------------   |:----------------  |:----------------|:----------------|
|08 |Unicoder-VL |AAAI-2020 |image-text |Trans |GR, MML, MOC |Single transformer encoder for VLP |[[Code](https://github.com/microsoft/Unicoder)]
|09 |VLP |AAAI-2020 |image-text |Trans |BiDT, Seq2seq |Unified encoder-decoder network architecture |[[Code](https://github.com/LuoweiZhou/VLP)] 
|10 |UNITER |ECCV-2020 |image-text |Trans |MRA, MML |Propose an OT-based Word-Region Alignment objective |[[Code](https://github.com/ChenRocks/UNITER)]  
|11 |12-IN-1  |CVPR-2020  |image-text |Trans |CS, GR |Training jointly on 12 different datasets in a multi-task learning manner |[[Code](https://github.com/facebookresearch/vilbert-multi-task)] 
|12 |VisDial-BERT |ECCV-2020 |image-text |Trans |MLM, NSP, MIR |Pre-training on image-text corpus and finetuning on visual dialog |[[Code](https://github.com/vmurahari3/visdial-bert/)]
|13 |ImageBERT |arXiv-2020 |image-text |Trans |MOC, MLM, MML, MOR |Indicating that multi-stage pre-training works better |-  
|14 |PREVALENT |CVPR-2020 |image-text |Trans |MLM, AP |Pre-training for vision and language navigation |[[Code](https://github.com/weituo12321/PREVALENT)] 
|15 |InterBERT |arXiv-2020 |image-text |Trans |MSM, MOC, ITM-hn |Finding that all-attention works better than co-attention for modal interaction |[[Code](https://github.com/black4321/InterBERT)] 
|16 |PixelBERT |arXiv-2020 |image-text |CNN, Trans |MLM, MML |First to align vision and language in pixel and text-level |- 
|17 |OSCAR |ECCV-2020 |image-text |Trans |CS, MLM |Use object tags as anchor points to align image regions with word embeddings |[[Code](https://github.com/microsoft/Oscar)] 
|18 |FashionBERT |RDIR-2020 |image-text |BERT |MLM, MOR, MML |Use image patches for fashion domain instead of RoIs |[[Code](https://github.com/alibaba/EasyTransfer)] 
|19 |VILLA |NeurIPS-2020 |image-text |Trans |MLM, MOR, MML |Pre-training with adversarial learning |[[Code](https://github.com/zhegan27/VILLA)] 
|20 |UniVL  |arXiv-2020  |video-text  |Trans  |MLM, MFM, MML, ITG  |A unified model for multimodal understanding and generation  |[[Code](https://github.com/microsoft/UniVL)]  
|21 |HERO  |EMNLP-2020  |video-text  |Trans  |MLM, MFM, VSM, FOM |Hierarchical Transformer-based model trained with newly proposed VSM and FOM  |[[Code](https://github.com/linjieli222/HERO)] 
|22 |MMFT-BERT  |EMNLP-2020  |image-text  |BERT  |Classification |Adopt multiModal fusion Transformer for modality fusion|[[Code](https://github.com/aurooj/MMFT-BERT)] 
|23 |ActBERT  |CVPR-2020 |image-text  |Trans |CS, GR  |Extract actions explicitly as one of the inputs  |-  
|24 |UNIMO  |arXiv-2020 |image-text  |Trans  |CS  |Adapt to single-, multi-modal understanding and generation tasks effectively  |[[Code](https://github.com/PaddlePaddle/Research/tree/master/NLP/UNIMO)]  






### Year 2019 and Before 
|**NO.**     | **Model**     | **Publish**        | **Modality**        | **Architecture**   | **Objective**     |**Highlights**   |**Code**         |
|:-----------|:-----------   |:----------------   |:----------------    |:----------------   |:----------------  |:----------------|:----------------|
|01 |VisualBERT |arXiv-2019 |image-text |Trans, BERT |GR, MML |A simple and strong baseline for VLP |[[Code](https://github.com/uclanlp/visualbert)]
|02 |ViLBERT |NeurIPS-2019 |image-text |Trans |CS, GR |First adopt co-attention for MM pre-training |[[Code](https://github.com/jiasenlu/vilbert_beta)] 
|03 |LXMERT |EMNLP-2019 |image-text |Trans | QA, MOR, MOC, MML, MLM |Propose a cross-modality encoder for vision-language pre-training |[[Code](https://github.com/airsplay/lxmert)] 
|04 |B2T2 |EMNLP-2019 |image-text |ResNet, BERT |MML, GR |Embed bounding box into text transformer in a early fusion manner |[[Code](https://github.com/google-research/language/tree/master/language/question_answering/b2t2)]  
|05 |VL-BERT |ICLR-2019 |image-text |BERT |GR, MOC |MM PTMs and faster rcnn are jointly trained |[[Code](https://github.com/jackroos/VL-BERT)] 
|06 |VideoBERT  |ICCV-2019 |video-text  |BERT  |MLM|A simple model for video-text feature learning |[[Code](https://github.com/ammesatyajit/VideoBERT)]  
|07 |CBT |arXiv-2019  |video-text  |Trans  |NCE  |Self-supervised contrastive bidirectional Transformer  |-  


















