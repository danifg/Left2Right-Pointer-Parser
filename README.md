# Left2Right-Pointer-Parser
This repository includes the code of the left-to-right parser with pointer networks described in NAACL paper [Left-to-Right Dependency Parsing with Pointer Networks](https://arxiv.org/abs/1903.08445). The implementation is based on the dependency parser by Ma et al. (2018) (https://github.com/XuezheMax/NeuroNLP2) and reuses part of its code, including data preparation and evaluating scripts.

A more efficient implementation of the left-to-right parser can be found in (https://github.com/danifg/SyntacticPointer). While this alternative version does not control the generation of cycles during decoding, it provides a faster batch decoding and includes a "parse" mode to test already-trained models. 

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
    
### Acknowledgments

This work has received funding from the European Research Council (ERC), under the European Union's Horizon 2020 research and innovation programme (FASTPARSE, grant agreement No 714150), from MINECO (FFI2014-51978-C2-2-R, TIN2017-85160-C2-1-R) and from Xunta de Galicia (ED431B 2017/01).
