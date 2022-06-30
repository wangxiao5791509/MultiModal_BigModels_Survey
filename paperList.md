* **The summary of mainstream multi-modal pre-trained big models.** 

### Year 2019 and Before 
|**NO.**     | **Model**     | **Publish**        | **Modality**        | **Architecture**   | **Objective**     |**Highlights**   |**Code**         |
|:-----------|:-----------   |:----------------   |:----------------    |:----------------   |:----------------  |:----------------|:----------------|
|01 |VisualBERT |arXiv-2019 |image-text |Trans, BERT |GR, MML |A simple and strong baseline for VLP |[[Code](https://github.com/uclanlp/visualbert)]
|02 |ViLBERT |NeurIPS-2019 |image-text |Trans |CS, GR |First adopt co-attention for MM pre-training |[[Code](https://github.com/jiasenlu/vilbert_beta)] 
|03 |LXMERT |EMNLP-2019 |image-text |Trans | QA, MOR, MOC, MML, MLM |Propose a cross-modality encoder for vision-language pre-training |[[Code](https://github.com/airsplay/lxmert)] 
|04 |B2T2 |EMNLP-2019 |image-text |ResNet, BERT |MML, GR |Embed bounding box into text transformer in a early fusion manner |[[Code](https://github.com/google-research/language/tree/master/language/question_answering/b2t2)]  
|06 |VL-BERT |ICLR-2019 |image-text |BERT |GR, MOC |MM PTMs and faster rcnn are jointly trained |[[Code](https://github.com/jackroos/VL-BERT)] 




### Year 2020 
|**NO.**     | **Model**     | **Publish**        | **Modality**        | **Architecture**   | **Objective**     |**Highlights**   |**Code**         |
|:-----------|:-----------   |:----------------   |:----------------    |:----------------   |:----------------  |:----------------|:----------------|
|05 |Unicoder-VL |AAAI-2020 |image-text |Trans |GR, MML, MOC |Single transformer encoder for VLP |[[Code](https://github.com/microsoft/Unicoder)]
|07 |VLP |AAAI-2020 |image-text |Trans |BiDT, Seq2seq |Unified encoder-decoder network architecture |[[Code](https://github.com/LuoweiZhou/VLP)] 
|08 |UNITER |ECCV-2020 |image-text |Trans |MRA, MML |Propose an OT-based Word-Region Alignment objective |[[Code](https://github.com/ChenRocks/UNITER)]  
|09 |12-IN-1  |CVPR-2020  |image-text |Trans |CS, GR |Training jointly on 12 different datasets in a multi-task learning manner |[[Code](https://github.com/facebookresearch/vilbert-multi-task)] 
|10 |VisDial-BERT |ECCV-2020 |image-text |Trans |MLM, NSP, MIR |Pre-training on image-text corpus and finetuning on visual dialog |[[Code](https://github.com/vmurahari3/visdial-bert/)]
|11 |ImageBERT |arXiv-2020 |image-text |Trans |MOC, MLM, MML, MOR |Indicating that multi-stage pre-training works better |-  
|12 |PREVALENT |CVPR-2020 |image-text |Trans |MLM, AP |Pre-training for vision and language navigation |[[Code](https://github.com/weituo12321/PREVALENT)] 
|14 |InterBERT |arXiv-2020 |image-text |Trans |MSM, MOC, ITM-hn |Finding that all-attention works better than co-attention for modal interaction |[[Code](https://github.com/black4321/InterBERT)] 
|15 |PixelBERT |arXiv-2020 |image-text |CNN, Trans |MLM, MML |First to align vision and language in pixel and text-level |- 
|16 |OSCAR |ECCV-2020 |image-text |Trans |CS, MLM |Use object tags as anchor points to align image regions with word embeddings |[[Code](https://github.com/microsoft/Oscar)] 
|18 |FashionBERT |RDIR-2020 |image-text |BERT |MLM, MOR, MML |Use image patches for fashion domain instead of RoIs |[[Code](https://github.com/alibaba/EasyTransfer)] 
|19 |VILLA |NeurIPS-2020 |image-text |Trans |MLM, MOR, MML |Pre-training with adversarial learning |[[Code](https://github.com/zhegan27/VILLA)] 










### Year 2021 
|**NO.**     | **Model**     | **Publish**        | **Modality**        | **Architecture**   | **Objective**     |**Highlights**   |**Code**         |
|:-----------|:-----------   |:----------------   |:----------------    |:----------------   |:----------------  |:----------------|:----------------|
|13 |XGPT |NLPCC-2021 |image-text |Trans |IC, MLM, IDA, MOR |Novel IDA pre-training; Share parameters between encoder and decoder |- 
|20 |ERNIE-ViL |AAAI-2021 |image-text |Trans |MOC, AttP, RelP, MLM, MOR, MML |Use the knowledge obtained from scene graph |[[Code](https://github.com/Muennighoff/vilio)] 
|21 |KVL-BERT |KBS-2021 |image-text |BERT |MOC, MLM |Integrate commonsense knowledge for visual commonsense reasoning |- 
|22 |VinVL |CVPR-2021 |image-text |Trans |MTL, 3-way CS |Verifying that visual feature matters in VLP, i.e., strong object detector brings better results |[[Code](https://github.com/pzzhang/VinVL)] 
|23 |VL-T5 |ICML-2021 |image-text |Trans |MLM, VQA, MML, VG, GC |Unified framework for VL via generating texts |[[Code](https://github.com/j-min/VL-T5)] 
|24 |ViLT |ICML-2021 |image-text |Trans |MLM, MML |Use linear embedding only for Fast VL transformer|[[Code](https://github.com/dandelin/vilt)] 
|25 |ALIGN |ICML-2021 |image-text |EfficientNet, BERT |CS |Milestone for image-text pre-training using noisy data  |- 
|26 |Kaleido-BERT |CVPR-2021 |image-text |Trans |MLM, MML, AKPM |Use saliency detector to generate multi-grained patches |[[Code](http://dpfan.net/Kaleido-BERT)] 
|27 |MDETR |ICCV-2021 |image-text |CNN+Trans |STP, MML |An end-to-end text-modulated detection system |[[Code](https://github.com/ashkamath/mdetr)] 
|28 |SOHO |CVPR-2021 |image-text |CNN+Trans |MLM, MOR, MML|Use a dynamic-updated visual dictionary for vision-language alignment |[[Code](https://github.com/researchmm/soho)] 
|29 |E2E-VLP |ACL-2021 |image-text |Trans |OBD, ITG |The first end-to-end pre-trained model for V+L understanding and generation |- 
|30 |PIM |NeurIPS-2021  |image-text |Trans |MLM, MML, MOR |Propose a inter-modality flow metric to measure and reveal vision and language fusion |- 
|31 |CLIP-ViL |arXiv-2021 |image-text |Trans |MLM, VQA, MML |Take the CLIP visual encoder as its visual backbone |[[Code](https://github.com/clip-vil/CLIP-ViL)] 
|32 |ALBEF |NeurIPS-2021 |image-text |Trans |CS, GR |Design a momentum model to address noisy data |[[Code](https://github.com/salesforce/ALBEF)]	 
|33 |SimVLM |arXiv-2021 |image-text |Trans |PrefixLM |Simple VL model using single PrefixLM pre-training objective only |- 
|34 |MURAL |arXiv-2021 |image-text |Trans |CS |Adopt multi-task contrastive learning objective (image-text, text-text) |- 
|35 |VLMo |arXiv-2021 |image-text |Trans |MLM, MML, CS |Jointly learns visual-, text-encoder and a fusion encoder |[[Code](https://aka.ms/vlmo)] 







### Year 2022 
|**NO.**     | **Model**     | **Publish**        | **Modality**        | **Architecture**   | **Objective**     |**Highlights**   |**Code**         |
|:-----------|:-----------   |:----------------   |:----------------    |:----------------   |:----------------  |:----------------|:----------------|
|17 |pyramidCLIP |arXiv-2022  |image-text |CNN+Trans |CS|Hierarchical image-text contrastive learning|- 
 




























































