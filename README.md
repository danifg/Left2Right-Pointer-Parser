# Left2Right-Pointer-Parser
This repository includes the code of the left-to-right parser with pointer networks described in NAACL paper [Left-to-Right Dependency Parsing with Pointer Networks](https://arxiv.org/abs/1903.08445). The implementation is based on the dependency parser by Ma et al. (2018) (https://github.com/XuezheMax/NeuroNLP2) and reuses part of its code, including data preparation and evaluating scripts.

### Requirements
This implementation requires Python 2.7, PyTorch 0.3.1 and Gensim >= 0.12.0. 

### Experiments
To train and test the parser, just include the paths for data and embeddings in the following script, and run it:

    ./scripts/run_L2R_parser.sh

### Citation
    @inproceedings{fernandez-gonzalez-gomez-rodriguez-2019-left,
        title = "Left-to-Right Dependency Parsing with Pointer Networks",
        author = "Fern{\'a}ndez-Gonz{\'a}lez, Daniel  and G{\'o}mez-Rodr{\'\i}guez, Carlos",
        booktitle = "Proceedings of the 2019 Conference of the North {A}merican Chapter of the Association for Computational    Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers)",
        month = jun,
        year = "2019",
        address = "Minneapolis, Minnesota",
        publisher = "Association for Computational Linguistics",
        url = "https://www.aclweb.org/anthology/N19-1076",
        doi = "10.18653/v1/N19-1076",
        pages = "710--716"
    }
