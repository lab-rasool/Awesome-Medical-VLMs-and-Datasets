## Awesome Vision-Language Models (VLMs) for Medical Report Generation (RG) and Visual Question Answering (VQA)

[Vision-Language Models for Medical Report Generation and Visual Question Answering: A Review](https://arxiv.org/abs/2403.02469) is the comprehensive review that includes:

* the latest publicly available VLMs specifically designed for medical RG and VQA;
* the essential background on computer vision, natural
language processing, and VLMs to ensure its accessibility for readers
without a machine learning background;
* the description of publicly available vision-language
datasets, encompassing medical image-text pairs or question-answer
pairs related to medical images;
* the detailed description of metrics employed for evaluating VLMs on report generation and visual question answering tasks;
* the discussion of current challenges in the field and various
potential research directions that could significantly shape the future
of medical VLMs.


### The list of medical VLMs

| Medical VLM | VQA | RG | Paper | Code | Year |
|------|------|------|------|------|------|
| MedViLL | + | + | [Moon et al.](https://ieeexplore.ieee.org/document/9894658) | [GitHub](https://github.com/SuperSupermoon/MedViLL) |2021|
| PubMedCLIP | + | - | [Eslami et al.](https://arxiv.org/abs/2112.13906) | [GitHub](https://github.com/sarahESL/PubMedCLIP) | 2021 |
| RepsNet | + | + | [Tanwani et al.](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_68) |  on request at [Site](https://sites.google.com/view/repsnet) ? | 2022 |
| BiomedCLIP | + | - | [Zhang et al.](https://arxiv.org/abs/2303.00915) | [Hugging Face](https://huggingface.co/microsoft/BiomedCLIP-PubMedBERT_256-vit_base_patch16_224) | 2023 |
| UniXGen | - | +|  [Lee et al.](https://arxiv.org/abs/2302.12172) | [GitHub](https://github.com/ttumyche/UniXGen) | 2023 |
| RAMM | + | - | [Yuan et al.](https://arxiv.org/abs/2303.00534) | [GitHub](https://github.com/GanjinZero/RAMM) | 2023 |
| X-REM | - | + | [Jeong et al.](https://arxiv.org/abs/2303.17579) | [GitHub](https://github.com/rajpurkarlab/X-REM) | 2023 |
| Visual Med-Alpaca | + | - | - | [GitHub](https://github.com/cambridgeltl/visual-med-alpaca) | 2023 |
| CXR-RePaiR-Gen | - | + | [Ranjit et al.](https://arxiv.org/abs/2305.03660) | - | 2023 |
| LLaVa-Med | + | - | [Li et al.](https://arxiv.org/abs/2306.00890) | [GitHub](https://github.com/microsoft/LLaVA-Med) | 2023 |
| XrayGPT | + | + | [Thawkar et al.](https://arxiv.org/abs/2306.07971) | [GitHub](https://github.com/mbzuai-oryx/XrayGPT) | 2023 |
| CAT-ViL DeiT | + | - | [Bai et al.](https://arxiv.org/abs/2307.05182) | [GitHub](https://github.com/longbai1006/CAT-ViL) | 2023 |
| MUMC | + | - | [Li et al.](https://link.springer.com/chapter/10.1007/978-3-031-43907-0_36) | [GitHub](https://github.com/pengfeiliHEU/MUMC) | 2023 |
| Med-Flamingo | + | - | [Moor et al.](https://arxiv.org/abs/2307.15189) | [GitHub](https://github.com/snap-stanford/med-flamingo) | 2023 |
| RaDialog | + | + | [Pellegrini et al.](https://arxiv.org/abs/2311.18681) | [GitHub](https://github.com/ChantalMP/RaDialog) | 2023 |

### The list of Medical Vision-Language Datasets

| Medical Dataset | Paper | Link |
|------|------|------|
| ROCO | [Pelka et al.](https://link.springer.com/chapter/10.1007/978-3-030-01364-6_20) | [GitHub](https://github.com/razorx89/roco-dataset) |
| MIMIC-CXR | [Johnson et al.](https://www.nature.com/articles/s41597-019-0322-0) | [PhysioNet](https://www.physionet.org/content/mimic-cxr/2.0.0/) |
| MIMIC-CXR-JPG | [Johnson et al.](https://arxiv.org/abs/1901.07042) | [PhysioNet](https://physionet.org/content/mimic-cxr-jpg/2.0.0/) |
| MIMIC-NLE | [Kayser et al.](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_67) | [GitHub](https://github.com/maximek3/MIMIC-NLE) |
| CXR-PRO | [Ramesh et al.](https://proceedings.mlr.press/v193/ramesh22a/ramesh22a.pdf) | [PhysioNet](https://physionet.org/content/cxr-pro/1.0.0/) |
| MS-CXR | [Boecking et al.](https://link.springer.com/chapter/10.1007/978-3-031-20059-5_1) | [PhysioNet](https://physionet.org/content/ms-cxr/0.1/) |
| IU-Xray or Open-I | [Demner-Fushman et al.](https://academic.oup.com/jamia/article/23/2/304/2572395) | [Openi](https://openi.nlm.nih.gov/faq#collection) |
| MedICaT | [Subramanian et al.](https://aclanthology.org/2020.findings-emnlp.191/) | [GitHub](https://github.com/allenai/medicat) |
| PMC-OA | [Lin et al.](https://arxiv.org/abs/2303.07240) | [Hugging Face](https://huggingface.co/datasets/axiong/pmc_oa) |
| SLAKE | [Liu et al.](https://ieeexplore.ieee.org/document/9434010) | [MedVQA](https://www.med-vqa.com/slake/) |
| VQA-RAD | [Lau et al.](https://www.nature.com/articles/sdata2018251) | [Osf](https://osf.io/89kps/) |
| PathVQA | [He et al.](https://arxiv.org/abs/2003.10286) | [GitHub](https://github.com/UCSD-AI4H/PathVQA) |
| VQA-Med 2019 | [Abacha et al.](https://ceur-ws.org/Vol-2380/paper_272.pdf) | [GitHub](https://github.com/abachaa/VQA-Med-2019) |
| VQA-Med 2020 | [Abacha et al.](https://ceur-ws.org/Vol-2696/paper_106.pdf) | [GitHub](https://github.com/abachaa/VQA-Med-2020) |
| VQA-Med 2021 | [Ionescu et al.](https://link.springer.com/chapter/10.1007/978-3-030-85251-1_23) | [GitHub](https://github.com/abachaa/VQA-Med-2021) |
| EndoVis 2017 | [Allan et al.](https://arxiv.org/abs/1902.06426) | [GitHub](https://github.com/longbai1006/Surgical-VQLA) |
| EndoVis 2018 | [Allan et al.](https://arxiv.org/abs/2001.11190) | image frames in [Challenge](https://endovissub2018-roboticscenesegmentation.grand-challenge.org/Data/) and the rest in [GitHub](https://github.com/longbai1006/Surgical-VQLA?tab=readme-ov-file) |

