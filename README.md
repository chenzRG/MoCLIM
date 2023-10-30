This repository contains implementations of our research works of CIKM23.


# [MoCLIM: Towards Accurate Cancer Subtyping via Multi-Omics Contrastive Learning with Omics-Inference Modeling]
[https://dl.acm.org/doi/10.1145/3583780.3614970]

Ziwei Yang, Zheng Chen, Yasuko Matsubara, and Yasushi Sakurai. 2023. MoCLIM: Towards Accurate Cancer Subtyping via Multi-Omics Contrastive Learning with Omics-Inference Modeling. In Proceedings of the 32nd ACM International Conference on Information and Knowledge Management (CIKM '23). Association for Computing Machinery, New York, NY, USA, 2895–2905. 

This paper introduced MoCLIM, a multi-omics contrastive learning framework for accurate cancer subtype identification. MoCLIM treats multi-omics integration as multi-modal learning and independently extracts representations from each type of omics data. These representations are then combined using a contrastive learn- ing framework anchored in transcriptomics.

---------------------------------------------------------------------------------------------------------------------


MoCLIM|  
:-------------------------:|
| <img width="430" alt="image" src="https://github.com/yangziwei96/CIKM23/blob/main/OV.png">
| <img width="430" alt="image" src="https://github.com/yangziwei96/CIKM23/blob/main/6_subtype.png">


## Description

You can find the implementation and details in the respective files of "[MoCLIM_main](https://github.com/yangziwei96/CIKM23/blob/main/MoCLIM_main.ipynb)" 



## Setup

You can install the required dependencies using pip.

```bash
pip install -r requirements.txt
```

If you're using other than CUDA 10.2, you may need to install PyTorch for the proper version of CUDA. See [instructions](https://pytorch.org/get-started/locally/) for more details.



## Citation
Please consider citing it accordingly based on your need:

@inproceedings{10.1145/3583780.3614970,
author = {Yang, Ziwei and Chen, Zheng and Matsubara, Yasuko and Sakurai, Yasushi},
title = {MoCLIM: Towards Accurate Cancer Subtyping via Multi-Omics Contrastive Learning with Omics-Inference Modeling},
year = {2023},
isbn = {9798400701245},
doi = {10.1145/3583780.3614970},
pages = {2895–2905},
booktitle = {Proceedings of the 32nd ACM International Conference on Information and Knowledge Management},
numpages = {11},
series = {CIKM '23}
}









