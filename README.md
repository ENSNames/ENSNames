## Ethereum Name Service (ENS) Names

### Overview
There have been efforts to build a decentralized name service that gives greater control to domain owners. The Ethereum Name Service (ENS) is a major example. Yet, no existing work has systematically studied this emerging system, particularly regarding security and misbehavior. To address this gap, we present the first large-scale measurement study of ENS. Our findings suggest that ENS has shown growth during its four years' evolution. We identify several security issues, including traditional name system problems, as well as new issues introduced by the unique properties of ENS. We find that attackers are abusing the system with thousands of squatting ENS names, a number of scam blockchain addresses and indexing of malicious websites. We further develop a new record persistence attack, to find that 22,716 .eth names (3.7\% of all names) are vulnerable to name hijacking. Our exploration suggests that our community should invest more effort into the detection and mitigation of issues in decentralized name services. 

### About the Dataset
There are 617,250 names in the dataset in total. And the dataset including hashes of names, names we restored, the owner of names and expiration time of names. You can click [here](https://github.com/ENSNames/ensnames) to download the dataset.

If you use our dataset in your research, please cite our paper: [https://dl.acm.org/doi/abs/10.1145/3517745.3561469](https://dl.acm.org/doi/abs/10.1145/3517745.3561469)
```
@inproceedings{xia2022challenges,
  title={Challenges in decentralized name management: the case of ENS},
  author={Xia, Pengcheng and Wang, Haoyu and Yu, Zhou and Liu, Xinyu and Luo, Xiapu and Xu, Guoai and Tyson, Gareth},
  booktitle={Proceedings of the 22nd ACM Internet Measurement Conference},
  pages={65--82},
  year={2022}
}
```
