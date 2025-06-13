# Training-Free Voice Conversion with Factorized Optimal Transport [Interspeech 2025]
By [Alexander Lobashev](https://linkedin.com/in/alexander-lobashev), [Assel Yermekova](https://linkedin.com/in/allessyer), [Maria Larchenko](https://scholar.google.com/citations?user=9sjCJ1IAAAAJ&hl=en)

[![arXiv](https://img.shields.io/badge/Paper-arXiv-red.svg)](https://www.arxiv.org/abs/2506.09709)

![graphical_abstract](./images/MKL-VC-github.png) 
We introduce Factorized MKL-VC, a training-free modification for kNN-VC pipeline. In contrast with original pipeline, our algorithm performs high quality any-to-any cross-lingual voice conversion with only 5 second of reference audio. MKL-VC replaces kNN regression with a factorized optimal transport map in WavLM embedding subspaces, derived from Monge-Kantorovich Linear solution. Factorization addresses non-uniform variance across dimensions, ensuring effective feature transformation. Experiments on LibriSpeech and FLEURS datasets show MKL-VC significantly improves content preservation and robustness with short reference audio, outperforming kNN-VC. MKL-VC achieves performance comparable to FACodec, especially in cross-lingual voice conversion domain.

This repository contains the source code and instructions for reproducing the results presented in our paper.

## Citation
```
@inproceedings{
alobashev25,
title={Training-Free Voice Conversion with Factorized Optimal Transport},
author={Alexander Lobashev and Assel Yermekova and Maria Larchenko},
booktitle={Twenty sixth edition of the Interspeech Conference},
year={2025},
url={https://www.arxiv.org/abs/2506.09709}
}
```



