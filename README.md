# MoCLIM: Towards Accurate Cancer Subtyping via Multi-Omics Contrastive Learning with Omics-Inference Modeling

This repository contains the implementations of MoCLIM, presented at the 32nd ACM International Conference on Information and Knowledge Management (CIKM '23).

Original paper: [https://dl.acm.org/doi/10.1145/3583780.3614970].

MoCLIM, developed by Ziwei Yang, Zheng Chen, Yasuko Matsubara, and Yasushi Sakurai, introduces a novel approach to cancer subtype identification using multi-omics contrastive learning with omics-inference modeling. 

---------------------------------------------------------------------------------------------------------------------
## Background

Omics Data for Cancer Subtyping|
:-------------------------:|
| <img width="800" alt="image" src="https://github.com/yangziwei96/MoCLIM/blob/main/bg.png">


## Motivation

Biological Observation: Transcriptomics as a Focal Point|
:-------------------------:|
| <img width="800" alt="image" src="https://github.com/yangziwei96/MoCLIM/blob/main/ob.png">


## Overview

MoCLIM Framework Overview|
:-------------------------:|
| <img width="800" alt="image" src="https://github.com/yangziwei96/MoCLIM/blob/main/OV.png">


## Results & Biomedical Evaluations

Cancer Subtyping Examples|
:-------------------------:|
| <img width="800" alt="image" src="https://github.com/yangziwei96/MoCLIM/blob/main/6_subtype.png">
Gene Set Enrichment Analysis Examples|
| <img width="800" alt="image" src="https://github.com/yangziwei96/MoCLIM/blob/main/gsea.png">


## Implementation Details

The implementation details and code can be found in the "[MoCLIM_main](https://github.com/yangziwei96/CIKM23/blob/main/MoCLIM_main.ipynb)". 
Make sure to follow the setup instructions below to run the code successfully.


## Setup

To set up the project environment, install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

If you're using a CUDA version other than 10.2, please ensure PyTorch is installed for the appropriate CUDA version. Refer to the [instructions](https://pytorch.org/get-started/locally/) for detailed instructions.


## Citation
If you find our work helpful for your research, please consider citing our paper:

    @inproceedings{MoCLIM,
  	author={Yang, Ziwei and Chen, Zheng and Matsubara, Yasuko and Sakurai, Yasushi},
  	booktitle = {Proceedings of the 32nd ACM International Conference on Information and Knowledge Management}, 
  	title={MoCLIM: Towards Accurate Cancer Subtyping via Multi-Omics Contrastive Learning with Omics-Inference Modeling}, 
  	year={2023},
  	series = {CIKM '23}
  	pages={2895–2905}}

Thank you for your interest in our research. For any questions or inquiries, feel free to reach out to us.
