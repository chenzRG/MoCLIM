This repository contains implementations of our research works of CIKM23.

# MoCLIM: Towards Accurate Cancer Subtyping via Multi-Omics Contrastive Learning with Omics-Inference Modeling
Original paper: [https://dl.acm.org/doi/10.1145/3583780.3614970]

Ziwei Yang, Zheng Chen, Yasuko Matsubara, and Yasushi Sakurai. 2023. MoCLIM: Towards Accurate Cancer Subtyping via Multi-Omics Contrastive Learning with Omics-Inference Modeling. In Proceedings of the 32nd ACM International Conference on Information and Knowledge Management (CIKM '23). Association for Computing Machinery, New York, NY, USA, 2895–2905. 

This paper introduced MoCLIM, a multi-omics contrastive learning framework for accurate cancer subtype identification. MoCLIM treats multi-omics integration as multi-modal learning and independently extracts representations from each type of omics data. These representations are then combined using a contrastive learn- ing framework anchored in transcriptomics.

---------------------------------------------------------------------------------------------------------------------

MoCLIM Framework Overview|
:-------------------------:|
| <img width="800" alt="image" src="https://github.com/yangziwei96/MoCLIM/blob/main/OV.png">
Cancer Subtyping Examples|
| <img width="800" alt="image" src="https://github.com/yangziwei96/MoCLIM/blob/main/6_subtype.png">


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
