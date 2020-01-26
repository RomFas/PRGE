# PRGE
Error detection in Knowledge Graphs: Path Ranking, Embeddings or both?

![alt text](https://github.com/RomFas/PRGE/blob/master/img/PRGE.png "PRGE Framework")

## Introduction
Here we provide the code for the Path Ranking Guided Embeddings (PRGE) framework. This is a hybrid approach that utilizes confidence scores from a Path Ranking method to Train Knowledge Graph Embeddings. 

## Scripts
- PRGE training script in src folder
  - Need to provide triples file and confidence scores file for training. Confidence scores can be obtained from any PRA method, here, we used PaTyBRED by Melo et al. (see [here](https://github.com/aolimelo/kged) and [here](https://dl.acm.org/doi/10.1145/3148011.3148033) for details)
- Evaluation notebooks for results (already run with provided results)

## Data
We provide already trained embeddings (download from [here](https://owncloud.skel.iit.demokritos.gr/index.php/s/Ba1z5YvtBGKGijj)) and additional files for 3 different datasets: 2 benchmark datasets (FB15K, WN18) and one custom dataset (Dementia, see here for more info). These embeddings can be directly used for the evaluation scripts. The additional files (triples/confidence scores) can be used to train the embeddings from scratch using the cpp script provided.  
