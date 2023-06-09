# ViCGCN
  
This repo contains code for our paper: Chau-Thang Phan, Quoc-Nam Nguyen, Chi-Thanh Dang, Trong-Hop Do, Kiet Van Nguyen. <a href="https://www.researchgate.net/publication/370003253_ViCGCN_Graph_Convolutional_Network_with_Contextualized_Language_Models_for_Social_Media_Mining_in_Vietnamese" target="_blank">ViCGCN: Contextualized Graph Neural Network for Social Media Mining in Vietnamese</a>

Please use the .ipynb files in these folders to execute.

## Introduction
We present a novel approach based on contextualized language model (PhoBERT) and graph-based method (Graph Convolutional Networks). In particular, the proposed approach, ViCGCN, jointly trained the power of **C**ontextualized embeddings with the ability of Graph Convolutional Networks, **GCN**, to capture more syntactic and semantic dependencies to address those drawbacks. Extensive experiments on various Vietnamese benchmark datasets were conducted to verify our approach. The observation shows that applying GCN to BERTology models as the final layer significantly improves performance. Moreover, the experiments demonstrate that ViCGCN outperforms 11 powerful baseline models, including BERTology models, fusion BERTology and GCN models, other baselines, and state-of-the-art methods on three benchmark social media datasets. Our proposed ViCGCN approach demonstrates a significant improvement of up to 10.74%, 10.58%, and 11.98% over the best Contextualized Language Models, including multilingual and monolingual, on three benchmark datasets, UIT-VSMEC, UIT-ViCTSD, and UIT-VSFC, respectively. Additionally, our integrated model ViCGCN achieves the best performance compared to other BERTology integrated with GCN models. 

## Citation

For any questions, please contact our corresponding author: Mr. Phan Chau Thang at 20520929@gm.uit.edu.vn.
