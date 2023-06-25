# PepPrCLIP
### *De Novo* Generation and Prioritization of Target-Binding Peptide Motifs from Sequence Alone 

![pepprclip](https://github.com/programmablebio/pepprclip/blob/main/pepprclip.png?raw=true)

Designing binders to target undruggable proteins presents a formidable challenge in drug discovery, requiring innovative approaches to overcome the lack of putative binding sites on pathogenic proteins. Recently, generative models have been trained to design binding proteins from the three-dimensional structure of a target protein alone, but thus exclude design to disordered or conformationally unstable targets. In this work, we provide a generalizable algorithmic framework to design short target-binding peptide motifs, requiring only the amino acid sequence of the target protein. To do this, we propose a process to generate naturalistic peptide candidates through Gaussian perturbation of the peptidic latent space of the state-of-the-art ESM-2 protein language model, and subsequently screen these *de novo* linear sequences for target-selective interaction activity via a CLIP-based contrastive learning architecture. By integrating these generative and discriminative steps, we create a unified **Pep**tide **Pr**ioritization via **CLIP** (**PepPrCLIP**) pipeline.

In this repository, you can find both the training code for PepPrCLIP as well as an easy-to-use, guided CoLab tutorial notebook to generate peptides for any input target anino acid sequence. 

We have also developed a user-friendly [Colab notebook](https://colab.research.google.com/drive/177k3Q57beUvXYrg8MQrS_QNmI9P9jlZu#scrollTo=gVHaTpIfYVQC) for peptide generation with PepPrCLIP!

Authors: Suhaas Bhat, Kalyan Palepu, Srikar Kavirayuni, and Pranam Chatterjee

Contact: pranam.chatterjee@duke.edu
