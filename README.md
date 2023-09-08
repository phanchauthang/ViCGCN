# ViCGCN
  
This repo contains code for our paper: Chau-Thang Phan, Quoc-Nam Nguyen, Chi-Thanh Dang, Trong-Hop Do, Kiet Van Nguyen. <a href="https://www.researchgate.net/publication/370003253_ViCGCN_Graph_Convolutional_Network_with_Contextualized_Language_Models_for_Social_Media_Mining_in_Vietnamese" target="_blank">ViCGCN: Contextualized Graph Neural Network for Social Media Mining in Vietnamese</a>

Please use the .ipynb files in these folders to execute.

## Introduction
We present a novel approach based on contextualized language model (PhoBERT) and graph-based method (Graph Convolutional Networks). In particular, the proposed approach, ViCGCN, jointly trained the power of **C**ontextualized embeddings with the ability of Graph Convolutional Networks, **GCN**, to capture more syntactic and semantic dependencies to address those drawbacks. Extensive experiments on various Vietnamese benchmark datasets were conducted to verify our approach. The observation shows that applying GCN to BERTology models as the final layer significantly improves performance. Moreover, the experiments demonstrate that ViCGCN outperforms **13** powerful baseline models, including BERTology models, fusion BERTology and GCN models, other baselines, and SOTA on three benchmark social media datasets. Our proposed ViCGCN approach demonstrates a significant improvement of up to 6.21%, 4.61%, and 2.63% over the best Contextualized Language Models, including multilingual and monolingual, on three benchmark datasets, UIT-VSMEC, UIT-ViCTSD, and UIT-VSFC, respectively. Additionally, our integrated model ViCGCN achieves the best performance compared to other BERTology integrated with GCN models. 

## Citation
For any usage related to all codes and data used from our repository, please cite our following paper:

```
@misc{phan2023vicgcn,
      title={ViCGCN: Graph Convolutional Network with Contextualized Language Models for Social Media Mining in Vietnamese}, 
      author={Chau-Thang Phan and Quoc-Nam Nguyen and Chi-Thanh Dang and Trong-Hop Do and Kiet Van Nguyen},
      year={2023},
      eprint={2309.02902},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

For any questions, please contact our corresponding author: Mr. Phan Chau Thang at 20520929@gm.uit.edu.vn.
