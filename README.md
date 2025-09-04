# Awesome OpenFHE

A curated list of amazing tools, products, tutorials, applications, publications, and other resources related to OpenFHE.

## Table of Contents

* [OpenFHE Software Interfaces](#openfhe-software-interfaces)
* [Documentation Resources](#documentation-resources)
* [Tutorials](#tutorials)
* [Products and Solutions using OpenFHE](#products-and-solutions-using-openfhe)
* [Hardware Acceleration](#hardware-acceleration)
* [Extensions of OpenFHE](#extensions-of-openfhe)
* [Lists of Open-Source User Projects](#lists-of-open-source-user-projects)
* [Videos of Conference Talks on Applications Implemented using OpenFHE](#videos-of-conference-talks-on-applications-implemented-using-openfhe)
* [Publications on Applications Implemented using OpenFHE](#publications-on-applications-implemented-using-openfhe)
* [Publications & Presentations on Private LLM Inference Implemented using OpenFHE](#publications-&-presentations-on-private-llm-inference-implemented-using-OpenFHE)
* [Publications Describing OpenFHE Crypto Algorithms](#publications-describing-openfhe-crypto-algorithms)
* [Publications with New Crypto Algorithms](#publications-with-new-crypto-algorithms)

## OpenFHE Software Interfaces

* [openfhe-development](https://github.com/openfheorg/openfhe-development) - Official C++ version.
* [openfhe-python](https://github.com/openfheorg/openfhe-python) - Official Python wrapper for OpenFHE.
* [openfhe-rs](https://github.com/fairmath/openfhe-rs) - Rust interface by FairMath.
* [openfhe-wasm](https://github.com/openfheorg/openfhe-wasm) - Official WebAssembly (NodeJS) port.
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

* [Duality Query](https://dualitytech.com/platform/duality-query/)
* [FHERMA](https://fherma.io/)
* [Google HEIR](https://github.com/google/heir)
* [Google Transpiler](https://github.com/google/fully-homomorphic-encryption)
* [OpenFHE-NumPy](https://github.com/openfheorg/openfhe-numpy)

## Hardware Acceleration

* [openfhe-hexl](https://github.com/openfheorg/openfhe-hexl) - Intel HEXL library backend for OpenFHE (for acceleration on Intel processors).
* [FIDESlib](https://github.com/CAPS-UMU/FIDESlib) - A server-side CKKS GPU library fully interoperable with OpenFHE.
* [OPENFHE-GPU-PUBLIC](https://github.com/leodec/openfhe-gpu-public) - A GPU library by Leo De Castro,  Antigoni Polychroniadou, and Daniel Escudero (J.P. Morgan).

## Extensions of OpenFHE

* [CHIFHE](https://github.com/SKLC-FHE/CHIFHE) - NTRU-based LMKCDEY scheme implementation.
* [CircuitBootstrap](https://github.com/LightFHE/CircuitBootstrap) - Circuit bootstrapping based on the improved LMKCDEY FHE scheme.
* [zkOpenFHE](https://github.com/zkFHE/zkOpenFHE) - A ZKP-augmented fork of the OpenFHE library.
* [palisade-abe](https://gitlab.com/palisade/palisade-abe) - Lattice-based IBE and ciphertext-policy ABE based on PALISADE (OpenFHE predecessor)
* [palisade-signature](https://gitlab.com/palisade/palisade-signature) - Lattice-based digital signature based on PALISADE (OpenFHE predecessor)
* [palisade-trapdoor](https://gitlab.com/palisade/palisade-trapdoor) - Lattice-based key-policy ABE, progam obfuscation, and subgaussian sampling based on PALISADE (OpenFHE predecessor)

## Lists of Open-Source User Projects

* [Contrib repository](https://github.com/openfheorg/contrib) - A curated list of open-source community-contributed projects based on OpenFHE.
* [Show & tell](https://openfhe.discourse.group/c/application/5) - Projects shared in the OpenFHE Discourse forum.
* [Diamond Indistinguishability Obfuscation](https://github.com/MachinaIO/diamond-io) - See the [blog post](https://machina-io.com/posts/hello_world_first.html) for more information.
* [Lightweight sorting using approximate homomorphic encryption](https://github.com/lorenzorovida/Lightweight-Sorting-In-Approximate-Homomorphic-Encryption) - See [paper](https://eprint.iacr.org/2025/1150) for more information.

## Videos of Conference Talks on Applications Implemented using OpenFHE

* [QRYPT: End-to-End Encrypted Audio Calls via Blind Audio Mixing (Nokia Bell Labs)](https://youtu.be/6FQX2otSbuE?t=2440) - Real Word Crypto 2025.
* [OpenFHE (with Focus on Applications)](https://youtu.be/uiI8bSdNkrg?si=bHvJibjcCqT6fjMh) - FHE.org Conference 2025.
* [Privacy-Preserving Collision-Risk Assessment for LEO Satellites](https://youtu.be/S7dmbaTR2ps?si=b5cUrrgzkDxEyf9r) - FHE.org Conference 2025.

## Publications on Applications Implemented using OpenFHE

Many of these publications have their open-source implementations available.

* [PrivTuner with homomorphic encryption and LoRA: a P3EFT scheme for privacy-preserving parameter-efficient fine-tuning of AI foundation models](https://arxiv.org/abs/2410.00433) - IEEE Transactions on Wireless Communications 2025.
* [Privacy-preserving cyberattack detection in blockchain-based IoT systems using AI and homomorphic encryption](https://arxiv.org/abs/2412.13522) - IEEE Internet of Things Journal 2025.
* [HyDia: FHE-based facial matching with hybrid approximations and diagonalization](https://petsymposium.org/popets/2025/popets-2025-0146.php) - PoPETS 2025.
* [Engorgio: an arbitrary-precision unbounded-size hybrid encrypted database via quantized fully homomorphic encryption](https://eprint.iacr.org/2025/198) - USENIX Security 2025.
* [Efficient ranking, order statistics, and sorting under CKKS](https://arxiv.org/abs/2412.15126) - USENIX Security 2025.
* [Secure and scalable gene expression quantification with pQuant](https://www.nature.com/articles/s41467-025-57393-6) - Nature Communications 2025.
* [HEPrune: fast private training of deep neural networks with encrypted data pruning](https://proceedings.neurips.cc/paper_files/paper/2024/file/5b26b9e634ba10f6c51c6db7365c4c28-Paper-Conference.pdf) - NeurIPS 2024.
* [Encrypted image classification with low memory footprint using fully homomorphic encryption](https://eprint.iacr.org/2024/460) - International Journal of Neural Systems 2024.
* [Towards efficient communication and secure federated recommendation system via low-rank training](https://arxiv.org/abs/2401.03748) - ACM Web Conference 2024.
* [Summation-based private segmented membership test from threshold-fully homomorphic encryption](https://eprint.iacr.org/2024/753) - PETS 2024.
* [Encrypted system identification as-a-service via reliable encrypted matrix inversion](https://ieeexplore.ieee.org/document/10886076) - IEEE Conference on Decision and Control 2024.
* [Towards secure AI-empowered vehicular networks: a federated learning approach using homomorphic encryption](https://ieeexplore.ieee.org/document/10757744) - IEEE Vehicular Technology Conference 2024.
* [Private pathological assessment via machine learning and homomorphic encryption](https://doi.org/10.1186/s13040-024-00379-9) - BioData Mining 2024. 
* [Improved multiplication-free biometric recognition under encryption](https://doi.org/10.1109/TBIOM.2023.3340306) - IEEE Transactions on Biometrics, Behavior, and Identity Science 2023.
* [Collaborative privacy-preserving analysis of oncological data using multiparty homomorphic encryption](https://www.pnas.org/doi/10.1073/pnas.2304415120) - Proceedings of the National Academy of Sciences (PNAS) 2023.
* [HELiKs: HE linear algebra kernels for secure inference](https://dl.acm.org/doi/10.1145/3576915.3623136) - ACM CCS 2023.
* [H3PC: enhanced security and privacy-preserving platoon construction based on fully homomorphic encryption](https://doi.org/10.1109/ITSC57777.2023.10422518) - IEEE International Conference on Intelligent Transportation Systems (ITSC) 2023.
* [HeSUN: homomorphic encryption for secure unbounded neural network inference](https://link.springer.com/chapter/10.1007/978-3-031-64948-6_21) - International Conference on Security and Privacy in Communication Systems 2023
* [A probabilistic design for practical homomorphic majority voting with intrinsic differential privacy](https://doi.org/10.1145/3605759.3625258) - WAHC 2023.
* [Secure large-scale genome-wide association studies using homomorphic encryption](https://www.pnas.org/doi/full/10.1073/pnas.1918257117) - Proceedings of the National Academy of Sciences (PNAS) 2020.

## Publications & Presentations on Private LLM Inference Implemented using OpenFHE

* [Latest trends and results in PPML using FHE](https://github.com/user-attachments/files/22145624/Yuriy_Polyakov_Latest_Trends_and_Results_in_PPML_using_FHE_v1.pdf) - CRYPTO PPML Workshop 2025.
* [Tricycle: private transformer inference with tricyclic encodings](https://eprint.iacr.org/2025/1200) - Cryptology ePrint Archive 2025.
* [Privacy-preserving large language model inference via GPU-accelerated fully homomorphic encryption](https://openreview.net/pdf?id=Rs7h1od6ov) - Neurips Safe Generative AI Workshop 2024.
* [Transformer-based language models and homomorphic encryption: an intersection with BERT-tiny](https://dl.acm.org/doi/10.1145/3643651.3659893) - 10th ACM International Workshop on Security and Privacy Analytics (2024).

## Publications Describing OpenFHE Crypto Algorithms

The algorithms in these publications are already implemented in the official distribution of OpenFHE. All of these papers have at least one co-author from the [OpenFHE design paper](https://eprint.iacr.org/2022/915) and most of these works were prepared as part of research projects advancing OpenFHE or its predecessors.

### FHE Algorithms
* [HRA-secure homomorphic lattice-based proxy re-encryption with tight security](https://eprint.iacr.org/2024/681) - IACR Communications in Cryptology (CiC) 2025.
* [Efficient FHEW bootstrapping with small evaluation keys, and applications to threshold homomorphic encryption](https://eprint.iacr.org/2022/198) - EUROCRYPT 2023.
* [High-precision RNS-CKKS on fixed but smaller word-size architectures: theory and application](https://eprint.iacr.org/2023/1462) - WAHC 2023.
* [Large-precision homomorphic sign evaluation using FHEW/TFHE bootstrapping](https://eprint.iacr.org/2021/1337) - ASIACRYPT 2022.
* [Approximate homomorphic encryption with reduced approximation error](https://eprint.iacr.org/2020/1118) - CT-RSA 2022.
* [Revisiting homomorphic encryption schemes for finite fields](https://eprint.iacr.org/2021/204) - ASIACRYPT 2021.
* [Bootstrapping in FHEW-like cryptosystems](https://eprint.iacr.org/2020/086) - WAHC 2021.
* [Implementation and performance evaluation of RNS variants of the BFV homomorphic encryption scheme](https://eprint.iacr.org/2018/589) - IEEE Transactions on Emerging Topics in Computing 2021.
* [An improved RNS variant of the BFV homomorphic encryption scheme](https://eprint.iacr.org/2018/117) - CT-RSA 2019.
* [FHEW: bootstrapping homomorphic encryption in less than a second](https://eprint.iacr.org/2014/816) - EUROCRYPT 2015.

### Lattice Trapdoor Sampling Algorithms
* [Implementing token-based obfuscation under (Ring) LWE](https://eprint.iacr.org/2018/1222) - WAHC 2020.
* [Building an efficient lattice gadget toolkit: subgaussian sampling and more](https://eprint.iacr.org/2018/946) - EUROCRYPT 2019.
* [Implementing conjunction obfuscation under entropic Ring LWE](https://eprint.iacr.org/2017/844) - IEEE Symposium on Security & Privacy (SP) 2018.
* [Faster Gaussian sampling for trapdoor lattices with arbitrary modulus](https://eprint.iacr.org/2017/308) - EUROCRYPT 2018.
* [Gaussian sampling over the integers: efficient, generic, constant-time](https://eprint.iacr.org/2017/259) - CRYPTO 2017.

## Publications with New Crypto Algorithms

OpenFHE was used to implement the new algorithms referenced below. Note that these algorithms have not been added to the official OpenFHE distribution yet.

* [General functional bootstrapping using CKKS](https://eprint.iacr.org/2024/1623) - CRYPTO 2025
* [NTRU-based bootstrapping for MK-FHEs without using overstretched parameters](https://eprint.iacr.org/2024/1898) - ASIACRYPT 2024
* [Circuit bootstrapping: faster and smaller](https://eprint.iacr.org/2024/323) - EUROCRYPT 2024
* [Faster NTRU-based bootstrapping in less than 4 ms](https://tches.iacr.org/index.php/TCHES/article/view/11683/11203) - IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES) 2024.
* [Fast and accurate: efficient full-domain functional bootstrap and digit decomposition for homomorphic computation](https://tches.iacr.org/index.php/TCHES/article/view/11263/10805) -  IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES) 2024.
* [Non-interactive private multivariate function evaluation using homomorphic table lookup](https://cic.iacr.org/p/1/3/19/pdf) - IACR Communications in Cryptology (CiC) 2024.
* [Fast blind rotation for bootstrapping FHEs](https://eprint.iacr.org/2023/1564) - CRYPTO 2023.

