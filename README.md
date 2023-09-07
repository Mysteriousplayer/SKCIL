# Semantic Knowledge Guided Class Incremental Learning

## Abstarct
> Driven by practical needs, research on Class-Incremental Learning (CIL) has received more and more attentions in recent years. A technical challenge to be conquered by CIL methods is the catastrophic forgetting problem, where the model’s performance improves rapidly on new classes while deteriorates drastically on old ones. The main causes behind catastrophic forgetting include network drifts, inter-class confusions, etc. In this paper, we propose a novel CIL method that solves the catastrophic forgetting problem from two aspects. First, to solve the inter-class confusion problem, we propose a novel Semantic knOwledge gUided ciL framework (SOUL) that consists of a CNN feature extractor and a Bi-GCN (Graph Convolutional Network) classifier. In each CIL session, we use the semantic knowledge extracted from the class labels to build two inter-class relation graphs among all the encountered old and new classes. Using these two relation graphs, we develop a Bi-GCN classifier to fuse two kinds of semantic relations in a balanced way, and then to transfer the inter-class relations from semantic modality to image classification weights. The entire SOUL framework is trained end-to-end by the standard BP algorithm, which optimizes the Bi-GCN classifier and the CNN feature extractor jointly. Second, to prevent the network drift, we develop the local topology preserving strategy that divides the global topological structure of the learned feature space into a set of local topological relations, and maintains these local relations at CIL session. Experimental evaluations demonstrate the state-of-the-art performance accuracies on benchmark image classification datasets.
***
## Paper link
https://ieeexplore.ieee.org/document/10083158
***
## Cite

> @ARTICLE{wang_2023, \
> &emsp;&emsp;&emsp;&emsp; author={Wang, Shaokun and Shi, Weiwei and Dong, Songlin and Gao, Xinyuan and Song, Xiang and Gong, Yihong}, \
> &emsp;&emsp;&emsp;&emsp; journal={IEEE Transactions on Circuits and Systems for Video Technology}, \
> &emsp;&emsp;&emsp;&emsp; title={Semantic Knowledge Guided Class-Incremental Learning}, \
> &emsp;&emsp;&emsp;&emsp; year={2023}, \
> &emsp;&emsp;&emsp;&emsp; volume={}, \
> &emsp;&emsp;&emsp;&emsp; number={}, \
> &emsp;&emsp;&emsp;&emsp; pages={1-1}, \
> &emsp;&emsp;&emsp;&emsp; doi={10.1109/TCSVT.2023.3262739}}

