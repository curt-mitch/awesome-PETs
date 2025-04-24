# Awesome PETs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for privacy-enhancing technologies

## Contents

- [Awesome PETs ](#awesome-pets-)
  - [Contents](#contents)
  - [General](#general)
    - [Articles](#articles)
    - [Books](#books)
    - [Blogs](#blogs)
    - [Papers](#papers)
    - [Podcasts](#podcasts)
  - [Differential Privacy](#differential-privacy)
    - [Organizations](#organizations)
    - [Blogs](#blogs-1)
    - [Books](#books-1)
    - [Open-Source Tools](#open-source-tools)
    - [Papers](#papers-1)
    - [Videos](#videos)
  - [Privacy-Preserving Federated Learning](#privacy-preserving-federated-learning)
    - [Papers](#papers-2)
    - [Open-Source Tools](#open-source-tools-1)
  - [Homomorphic Encryption](#homomorphic-encryption)
    - [Organizations](#organizations-1)
    - [Blogs](#blogs-2)
  - [Secure Multiparty Computation](#secure-multiparty-computation)
    - [Organizations](#organizations-2)
    - [Videos](#videos-1)
  - [Synthetic Data](#synthetic-data)
    - [Tools](#tools)
  - [Zero-knowledge Proofs and zk-SNARKs](#zero-knowledge-proofs-and-zk-snarks)
    - [Organizations](#organizations-3)
    - [Blogs and Tutorials](#blogs-and-tutorials)
    - [Papers](#papers-3)
    - [Videos](#videos-2)
  - [Privacy-preserving Hardware](#privacy-preserving-hardware)
    - [Blogs](#blogs-3)
  - [Contribute](#contribute)

## General

General resources about PETs and related concepts

For general privacy tools and services, see the **Awesome Privacy List** (github: [pluja/awesome-privacy](https://github.com/pluja/awesome-privacy)).

### Articles

- [Privacy Enhancing Technologies: An Introduction for Technologists](https://martinfowler.com/articles/intro-pet.html) - Overview of PETs from Katharine Jarmul, the author of Practical Data Privacy.

### Books

- [Practical Data Privacy](https://www.oreilly.com/library/view/practical-data-privacy/9781098129453/) - An overview of privacy and how to apply it in technical systems and organizations. Includes introductions to various PETs.

- [Real World Cryptography](https://www.manning.com/books/real-world-cryptography) - The majority of the book is an introduction to cryptography and cryptographic applications with additional material covering PETs such as multi-party computation, homomorphic encryption, zero-knowledge proofs, and cryptographic hardware.

### Blogs

- [OpenMined Blog](https://blog.openmined.org/) - Blog of the open-source group OpenMined with several posts on PETs and privacy tech.

### Papers

- [Privacy enhancing technologies: Adoption guide](https://www.gov.uk/government/publications/privacy-enhancing-technologies-adoption-guide) - A white paper and interactive tool on adopting PETs for projects provided by the UK government's Centre for Data Ethics and Innovation.

- [The United Nations Guide on Privacy-Enhancing Technologies for Official Statistics](https://unstats.un.org/bigdata/task-teams/privacy/guide/2023_UN%20PET%20Guide.pdf)

### Podcasts

- [Shifting Privacy Left](https://shiftingprivacyleft.com/) - Podcast hosted by privacy and legal expert Debra J Farber featuring interviews and discussions with various privacy and PETs experts.

## Differential Privacy

See the **Awesome Differential Privacy List** (github: [menisadi/awesome-differential-privacy](https://github.com/menisadi/awesome-differential-privacy)).

### Organizations

- [DifferentialPrivacy.org](https://differentialprivacy.org/) - A website with resources curated by the DP research community. It includes several courses, videos, surveys, and links to other resources.

- [OpenDP](https://opendp.org/) - Open-source group developing DP tools.

### Blogs

- [NIST Differential Privacy Blog Series](https://www.nist.gov/itl/applied-cybersecurity/privacy-engineering/collaboration-space/focus-areas/de-id/blog-series-1) - A blog series from NIST covering topics from introductory concepts to deploying DP-based applications.

- [A friendly, non-technical introduction to differential privacy](https://desfontain.es/privacy/friendly-intro-to-differential-privacy.html) - A useful series of posts and visualizations introducing DP and related concepts from Damien Desfontaines, a.k.a. Ted, a research scientist at [Tumult Labs](https://www.tmlt.io/).

### Books

- [The Algorithmic Foundations of Differential Privacy](https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf) - Free, online book focused on DP principles and theory

- [Programming Differential Privacy](https://programming-dp.com/) - Free, online book focused on teaching DP principles through Python code examples

- [Hands-On Differential Privacy](https://www.oreilly.com/library/view/hands-on-differential-privacy/9781492097730/) - An O'Reilly book analyzing practical DP methods with a focus on using the OpenDP library

### Open-Source Tools

- [OpenDP](https://github.com/opendp/opendp) - Python bindings for OpenDP's Rust-based framework.

### Papers

- [Guidelines for Evaluating Differential Privacy Guarantees](https://csrc.nist.gov/pubs/sp/800/226/ipd) - NIST publication providing an overview of DP with a focus on practical considerations and common pitfalls when using DP in practice.

- [Differential Privacy: A Primer for a Non-Technical Audience](https://scholarship.law.vanderbilt.edu/jetlaw/vol21/iss1/4/) - In-depth yet accessible overview of DP.

- [Issues Encountered Deploying Differential Privacy](https://arxiv.org/abs/1809.02201) - Review of deployment and usage of DP for the 2020 United States population census.

- [Differential Privacy & the 2020 U.S. Census Reading List](https://priyakalot.github.io/DP-census/) - Collection of writings and presentations reviewing the usage of DP in the 2020 U.S. Census.

### Videos

- [Protecting Privacy with MATH](https://www.youtube.com/watch?v=pT19VwBAqKA) - Overview of DP and related concepts by the [MinutePhysics](https://www.youtube.com/@MinutePhysics) channel in collaboration with the US Census Bureau.

## Privacy-Preserving Federated Learning

**Note**: Federated learning by itself does not guarantee data privacy, but when used in combination with other PETs it can become privacy-preserving.

There are several different Awesome lists for federated learning, but this one seems to be the most popular. Note that it's federated learning generally, not just PPFL: [https://github.com/innovation-cat/Awesome-Federated-Machine-Learning](https://github.com/innovation-cat/Awesome-Federated-Machine-Learning)

### Papers

- [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/abs/1602.05629) - Paper that introduced the popular FedAvg algorithm

### Open-Source Tools

- [APPFL](https://github.com/APPFL/APPFL) - Advanced Privacy-Preserving Federated Learning built my Argonne National Labs aimed at high-performance computing applications. Includes differential-privacy and the ability to incorporate other PETs

- [FedML](https://www.fedml.ai/) - Github Repository: [https://github.com/fedml-ai/fedml](https://github.com/fedml-ai/fedml)

- [FedScale](https://fedscale.ai/) - An open-source FL framework supported by [SymbioticLab](https://symbioticlab.org/) at the University of Michigan, Ann Arbor.

- [Flower](https://flower.dev/) - A unified FL framework available in multiple languages. Flower does include some privacy features under active development, such as differential privacy and secure aggregation.

- [FLUTE](https://github.com/microsoft/msrflute) - A platform for conducting FL simulations supported by Microsoft.

- [OpenFL](https://github.com/securefederatedai/openfl) - Open-source FL framework hosted by the Linux Foundation.

- [pfl](https://apple.github.io/pfl-research/) - A Python framework developed by Apple for efficient PPFL simulations.

- [Tensorflow Federated](https://www.tensorflow.org/federated) - A federated instance of the popular Tensorflow ML library.

## Homomorphic Encryption

See the **Awesome Homomorphic Encryption List** (github: [jonaschn/awesome-he](https://github.com/jonaschn/awesome-he)).

### Organizations

- [https://homomorphicencryption.org/](Homomorphic Encryption Standardization) - A body consisting of industry, government, and academic members advocating for standardization of HE.

### Blogs

- [A High-Level Technical Overview of Fully Homomorphic Encryption](https://www.jeremykun.com/2024/05/04/fhe-overview/) - Great overview of FHE from Jeremy Kun's Math ∩ Programming blog

## Secure Multiparty Computation

See the **Awesome MPC List** (github: [rdragos/awesome-mpc](https://github.com/rdragos/awesome-mpc)).

### Organizations

- [MPC Alliance](https://www.mpcalliance.org/) - Industry group devoted to increasing adoption of MPC. Includes links to several books and videos.

### Videos

- [Multiparty Computation - Computational Thinking](https://www.youtube.com/watch?v=5qzNe1hk0oY) - 5 minute intro on MPC and secret sharing examples and concepts

## Synthetic Data

### Tools

[DataSynthesizer](https://github.com/DataResponsibly/DataSynthesizer) - A Python-based tool for generating differentally-private synthetic data

## Zero-knowledge Proofs and zk-SNARKs

See the **Awesome Zero Knowledge Proofs List** (github: [https://github.com/matter-labs/awesome-zero-knowledge-proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs))

### Organizations

- [ZKProof](https://zkproof.org/) - An open-industry academic initiative seeking to develop standards for ZKPs. The organization also conducts workshops, publishes research, educational material, etc.

### Blogs and Tutorials

- [Zero Knowledge What? An Introduction to Zero Knowledge](https://codethechange.stanford.edu/guides/guide_zk.html) - A technical introduction (including basic Python examples) from Stanford's [Code the Change](https://codethechange.stanford.edu/#/) guides.

- [Zero-Knowledge: a tutorial by Oded Goldreich](https://www.wisdom.weizmann.ac.il/~oded/zk-tut02.html) - A tutorial covering introductory and advanced topics in Zero-knowledge proofs

### Papers

- [The knowledge complexity of interactive proof-systems](https://dl.acm.org/doi/10.1145/22145.22178) - The original paper introducing zero-knowledge proofs

- [A physical zero-knowledge object-comparison system for nuclear warhead verification](https://arxiv.org/abs/1602.07717) - A proposed mechanism to use ZKPs for nuclear armament reduction

- [Why and How zk-SNARK Works](https://arxiv.org/abs/1906.07221) - Good overview of the building blocks that zk-SNARKs are composed of

### Videos

- [Zero Knowledge Proofs - Computational Thinking](https://www.youtube.com/watch?v=5qzNe1hk0oY) - 9 minute intro on ZKP examples and concepts

## Privacy-preserving Hardware

### Blogs

- [State of the Future - Trusted Execution Environments (TEEs) and Confidential Computing](https://stateofthefuture.substack.com/p/e19-trusted-execution-environments) - Overview from a VC blog on what trusted-execution environments are and how they enable privacy-preserving, collaborative computing

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
