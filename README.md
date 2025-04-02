# Awesome OpenFHE

A curated list of amazing tools, products, tutorials, applications, publications, and other resources related to OpenFHE.

## Table of Contents

* [OpenFHE Software Interfaces](#openfhe-software-interfaces)
* [Documentation Resources](#documentation-resources)
* [Tutorials](#tutorials)
* [Products and Solutions using OpenFHE](#products-and-solutions-using-openfhe)
* [Extensions of OpenFHE](#extensions-of-openfhe)
* [Lists of Open-Source User Projects](#lists-of-open-source-user-projects)
* [Publications on Applications Implemented using OpenFHE](#publications-on-applications-implemented-using-openfhe)
* [Publications Describing OpenFHE Crypto Algorithms](#publications-describing-openfhe-crypto-algorithms)
* [Publications with New Crypto Algorithms](#publications-with-new-crypto-algorithms)

## OpenFHE Software Interfaces

* [openfhe-development](https://github.com/openfheorg/openfhe-development) - Official C++ version.
* [openfhe-python](https://github.com/openfheorg/openfhe-python) - Official Python wrapper for OpenFHE.
* [openfhe-rs](https://github.com/fairmath/openfhe-rs) - Rust inteface by FairMath.
* [openfhe-julia](https://github.com/hpsc-lab/openfhe-julia) - Julia interface led by Prof. Michael Schlottke-Lakemper, University of Augsburg.

## Documentation Resources

* [ReadTheDocs documentation](https://openfhe-development.readthedocs.io/en/latest/) - Main documentation for OpenFHE.
* [Community Discourse Forum](https://openfhe.discourse.group/) - Covers OpenFHE and general FHE questions.
* [Education](https://github.com/openfheorg/education) - Educational resources on FHE and OpenFHE led by Prof. Bill Buchanan, Edinburgh Napier University.

## Tutorials

* [Homomorphic Encryption using OpenFHE](https://www.youtube.com/watch?v=1aeasUAoUAA) - August 2024.
* [OpenFHE AAAI 2024 Tutorial (Python)](https://github.com/openfheorg/aaai-2024-lab-materials) - February 2024.
* [PALISADE (OpenFHE predecessor) webinars](https://openfhe.org/webinars/) - 2020 to 2021

## Products and Solutions using OpenFHE

* [Duality Query Engine](https://dualitytech.com/platform/duality-query/)
* [FHERMA](https://fherma.io/)
* [Google HEIR](https://github.com/google/heir)
* [Google Transpiler](https://github.com/google/fully-homomorphic-encryption)

## Extensions of OpenFHE

* [openfhe-hexl](https://github.com/openfheorg/openfhe-hexl) - Intel HEXL library backend for OpenFHE (for acceleration on Intel processors).
* [CHIFHE](https://github.com/SKLC-FHE/CHIFHE) - NTRU-based LMKCDEY scheme implementation.
* [CircuitBootstrap](https://github.com/LightFHE/CircuitBootstrap) - Circuit bootstrapping based on the improved LMKCDEY FHE scheme.
* [zkOpenFHE](https://github.com/zkFHE/zkOpenFHE) - A ZKP-augmented fork of the OpenFHE library.

## Lists of Open-Source User Projects

* [Contrib repository](https://github.com/openfheorg/contrib) - A curated list of open-source community-contributed projects based on OpenFHE.
* [Show & tell](https://openfhe.discourse.group/c/application/5) - Projects shared in the OpenFHE Discourse forum.

## Publications on Applications Implemented using OpenFHE

Many of these publications have their open-source implementations available.
* [Engorgio: An Arbitrary-Precision Unbounded-Size Hybrid Encrypted Database via Quantized Fully Homomorphic Encryption](https://eprint.iacr.org/2025/198) - USENIX Security 2025.
* [Efficient ranking, order statistics, and sorting under CKKS](https://arxiv.org/abs/2412.15126) - USENIX Security 2025.
* [Secure and scalable gene expression quantification with pQuant](https://www.nature.com/articles/s41467-025-57393-6) - Nature Communications 2025.
* [HEPrune: fast private training of deep neural networks with encrypted data pruning](https://proceedings.neurips.cc/paper_files/paper/2024/file/5b26b9e634ba10f6c51c6db7365c4c28-Paper-Conference.pdf) - NeurIPS 2024.
* [Encrypted image classification with low memory footprint using fully homomorphic encryption](https://eprint.iacr.org/2024/460) - International Journal of Neural Systems 2024.
* [Towards efficient communication and secure federated recommendation system via low-rank training](https://arxiv.org/abs/2401.03748) - ACM Web Conference 2024.
* [Summation-based private segmented membership test from threshold-fully homomorphic encryption](https://eprint.iacr.org/2024/753) - PETS 2024.
* [Encrypted system identification as-a-service via reliable encrypted matrix inversion](https://ieeexplore.ieee.org/document/10886076) - IEEE Conference on Decision and Control 2024.
* [Towards secure AI-empowered vehicular networks: a federated learning approach using homomorphic encryption](https://ieeexplore.ieee.org/document/10757744) - IEEE Vehicular Technology Conference 2024.
* [Improved multiplication-free biometric recognition under encryption](https://doi.org/10.1109/TBIOM.2023.3340306) - IEEE Transactions on Biometrics, Behavior, and Identity Science 2023.
* [Collaborative privacy-preserving analysis of oncological data using multiparty homomorphic encryption](https://www.pnas.org/doi/10.1073/pnas.2304415120) - Proceedings of the National Academy of Sciences (PNAS) 2023.
* [HELiKs: HE linear algebra kernels for secure inference](https://dl.acm.org/doi/10.1145/3576915.3623136) - ACM CCS 2023.
* [H3PC: enhanced security and privacy-preserving platoon construction based on fully homomorphic encryption](https://doi.org/10.1109/ITSC57777.2023.10422518) - IEEE International Conference on Intelligent Transportation Systems (ITSC) 2023.
* [HeSUN: homomorphic encryption for secure unbounded neural network inference](https://link.springer.com/chapter/10.1007/978-3-031-64948-6_21) - International Conference on Security and Privacy in Communication Systems 2023
* [A probabilistic design for practical homomorphic majority voting with intrinsic differential privacy](https://doi.org/10.1145/3605759.3625258) - WAHC 2023.
* [Secure large-scale genome-wide association studies using homomorphic encryption](https://www.pnas.org/doi/full/10.1073/pnas.1918257117) - Proceedings of the National Academy of Sciences (PNAS) 2020.

## Publications Describing OpenFHE Crypto Algorithms

The algorithms in these publications are already included in the official versions of OpenFHE.

* [HRA-secure homomorphic lattice-based proxy re-encryption with tight security](https://eprint.iacr.org/2024/681) - IACR Communications in Cryptology (CiC) 2025.
* [Efficient FHEW bootstrapping with small evaluation keys, and applications to threshold homomorphic encryption](https://eprint.iacr.org/2022/198) - EUROCRYPT 2023.
* [Large-precision homomorphic sign evaluation using FHEW/TFHE bootstrapping](https://eprint.iacr.org/2021/1337) - ASIACRYPT 2022.
* [Approximate homomorphic encryption with reduced approximation error](https://eprint.iacr.org/2020/1118) - CT-RSA 2022.
* [Revisiting homomorphic encryption schemes for finite fields](https://eprint.iacr.org/2021/204) - ASIACRYPT 2021.
* [Bootstrapping in FHEW-like cryptosystems](https://eprint.iacr.org/2020/086) - WAHC 2021.
* [Implementation and performance evaluation of RNS variants of the BFV homomorphic encryption scheme](https://eprint.iacr.org/2018/589) - IEEE Transactions on Emerging Topics in Computing 2021.
* [An improved RNS variant of the BFV homomorphic encryption scheme](https://eprint.iacr.org/2018/117) - CT-RSA 2019.

## Publications with New Crypto Algorithms

OpenFHE was used to implement the new algorithms referenced below. Note that these algorithms have not been added to the official OpenFHE distribution yet.

* [Circuit bootstrapping: faster and smaller](https://eprint.iacr.org/2024/323) - EUROCRYPT 2024
* [Faster NTRU-based bootstrapping in less than 4 ms](https://tches.iacr.org/index.php/TCHES/article/view/11683/11203) - IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES) 2024.
* [Fast and accurate: efficient full-domain functional bootstrap and digit decomposition for homomorphic computation](https://tches.iacr.org/index.php/TCHES/article/view/11263/10805) -  IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES) 2024.
* [Non-interactive private multivariate function evaluation using homomorphic table lookup](https://cic.iacr.org/p/1/3/19/pdf) - IACR Communications in Cryptology (CiC) 2024.
* [Fast blind rotation for bootstrapping FHEs](https://eprint.iacr.org/2023/1564) - CRYPTO 2023.
* [High-precision RNS-CKKS on fixed but smaller word-size architectures: theory and application](https://eprint.iacr.org/2023/1462) - WAHC 2023.

