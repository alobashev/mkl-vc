# [Interspeech 2025] Training-Free Voice Conversion with Factorized Optimal Transport

This repository contains the source code and instructions for reproducing the results presented in our Interspeech 2025 paper "Training-Free Voice Conversion with Factorized Optimal Transport" by Alexander Lobashev, Assel Yermekova and Maria Larchenko.

Abstract.

This paper introduces Factorized MKL-VC, a training-free modification for kNN-VC pipeline.
In contrast with original pipeline, our algorithm performs high quality any-to-any cross-lingual voice conversion with only 5 second of reference audio. MKL-VC replaces kNN regression with a factorized optimal transport map in WavLM embedding subspaces, derived from Monge-Kantorovich Linear solution. Factorization addresses non-uniform variance across dimensions, ensuring effective feature transformation. Experiments on LibriSpeech and FLEURS datasets show MKL-VC significantly improves content preservation and robustness with short reference audio, outperforming kNN-VC. MKL-VC achieves performance comparable to FACodec, especially in cross-lingual voice conversion domain.
