# Left2Right-Pointer-Parser
This repository includes the code of the left-to-right parser with pointer networks described in NAACL paper [Left-to-Right Dependency Parsing with Pointer Networks](https://arxiv.org/abs/1903.08445). The implementation is based on the dependency parser with stack-pointer networks by Ma et al. (2018) (https://github.com/XuezheMax/NeuroNLP2) and reuses part of its code, including data preparation and evaluating scripts.

### Requirements
This implementation requires Python 2.7, PyTorch >=0.3.0 and Gensim >= 0.12.0. 

### Experiments
To train and test the parser, just include the paths for data and embeddings and run:

    ./scripts/run_L2R_parser.sh

