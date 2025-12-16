# MG-STRING: Approximate Abelianity in Multi-Generator Cayley-STRING: A Flexible Framework for Relative Positional Encoding
This repo contains the implementation of **MG-STRING**, an approximately abelian, learnable, sparse, and multi-generator variant of the Cayley-STRING relative positional encoding mechanism. 

The codebase includes:
- **RoPE**, **Cayley-STRING**, **Sparse Cayley-STRING**
- **MG1**, **MG4**, and sparse MG variants
- Training / evaluation pipelines for **MNIST** and **CIFAR-10**
- Metrics for **relative-position consistency**, **commutator norms**, and **orthogonality error**

The notebook can be run as-is to re-train the models. To get metrics from trained models, please download the .pt files from [this link](https://drive.google.com/drive/folders/15u0IL766ar1cmdn5C64Fr1DeGJ1wsAr0?usp=sharing) then place them inside the models directory.
