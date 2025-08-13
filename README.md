# <a href="https://link.springer.com/book/10.1007/978-3-031-64087-2" target="_blank">"Deep Generative Modeling"</a>

<img src="figures/1726858979519.jpeg" alt="Deep Generative Modeling">

This first comprehensive book on models behind Generative AI has been thoroughly revised to cover all major classes of deep generative models: mixture models, Probabilistic Circuits, Autoregressive Models, Flow-based Models, Latent Variable Models, GANs, Hybrid Models, Score-based Generative Models, Energy-based Models, and Large Language Models. In addition, Generative AI Systems are discussed, demonstrating how deep generative models can be used for neural compression, among others.<br>

Deep Generative Modeling is designed to appeal to curious students, engineers, and researchers with a modest mathematical background in undergraduate calculus, linear algebra, probability theory, and the basics of machine learning, deep learning, and programming in Python and PyTorch (or other deep learning libraries). It should find interest among students and researchers from a variety of backgrounds, including computer science, engineering, data science, physics, and bioinformatics who wish to get familiar with deep generative modeling. In order to engage with a reader, the book introduces fundamental concepts with specific examples and code snippets. <br>

The aim of the book is to outline the most important techniques in deep generative modeling and, eventually, enable readers to formulate new models and implement them.


# Table of Content
<b>Front matter</b><br>
<b>Foreword</b> by <a href="https://scholar.google.com/citations?user=8200InoAAAAJ&hl=en" target="_blank">Prof. Max Welling</a><br>
<b>Preface</b><br>

1. Mixture of Gaussians (MoGs): a mixture of Gaussians 
2. Autoregressive Models (ARMs): ARMs parameterized with Causal Convolutionas and Transformers
3. Flow-based models (flows): RealNVP and IDFs (Integer Discrete Flows)
4. Variational Auto-Encoders (VAEs): a plain VAE and various priors, a hierarchical VAE
5. Diffusion-based Deep Generative Models (DDGMs): a Gaussian forward diffusion
6. Score-based Generative Models (SBGMs): score matching, score-based generative models, (conditional) flow matching
7. Hybrid modeling
8. Energy-based Models
9. Generative Adversarial Networks (GANs)
10. Neural Compression with Deep Generative Modeling
11. Large Language Models (LLMs)

<b>Appendix</b><br>
A. Useful Facts from Algebra and Calculus<br>
B. Useful Facts from Probability Theory and Statistics<br>


# Where to buy this book?
<a href="https://link.springer.com/book/10.1007/978-3-031-64087-2" target="_blank">Springer</a> <a href="https://www.amazon.com/Deep-Generative-Modeling-Jakub-Tomczak/dp/B0D4TR44GC/ref=pd_lpo_d_sccl_1/141-8785977-2759647?pd_rd_w=iL2rQ&content-id=amzn1.sym.4c8c52db-06f8-4e42-8e56-912796f2ea6c&pf_rd_p=4c8c52db-06f8-4e42-8e56-912796f2ea6c&pf_rd_r=4WYYB5T34DKDSVX6XM9M&pd_rd_wg=jAwdr&pd_rd_r=65b42a42-54af-4529-af17-39c1822dc745&pd_rd_i=B0D4TR44GC&psc=1" target="_blank">Amazon</a>


# Introductory examples to Deep Generative Models
The examples might look oversimplistic but that's the point! My idea is that everyone is able to follow every line of the code, and run the experiments within a couple of minutes on almost any laptop or computer. My goal is to encourage people who are new to understand and play with deep generative models. More advanced users, on the other hand, could refresh their knowledge or build on top of that to quickly check their ideas. Either way, I hope the code will help everyone to join a fascinating journey on deep generative modeling!


# Requirements
In all examples, we used:
- `pytorch 1.7.0`
- `numpy 1.17.2`
- `matplotlib 3.1.1`
- `scikit-learn 0.21.3`
- `pytorch-model-summary 0.1.1`
- `jupyter 1.0.0`


# Examples
All examples of implemented deep generative models are provided as jupyter notebooks. They can be find in the following folders:
1. [`mog`](https://github.com/jmtomczak/intro_dgm/tree/main/mog): an example of a mixture of Gaussians with equiprobable components or trainable component probabilities. 
2. [`arms`](https://github.com/jmtomczak/intro_dgm/tree/main/arms): an example of an autoregressive model with a causal convolutiona layer in 1D and transformers.
3. [`flows`](https://github.com/jmtomczak/intro_dgm/tree/main/flows): an example of a flow-based model, namely, RealNVP with coupling layers and permutation layers, and IDFs (Integer Discrete Flows).
4. [`vaes`](https://github.com/jmtomczak/intro_dgm/tree/main/vaes): (i) an example of a Variational Auto-Encoder using fully-connected layers and a standard Gaussian prior, (ii) an example of various priors for VAEs, (iii) an example of a hierarchical VAE.
5. [`ddgms`](https://github.com/jmtomczak/intro_dgm/tree/main/ddgms): an example of a Diffusion-based Deep Generative Model using a Gaussian forward diffusion with a fixed variace and a reverse diffusion parameterized by an MLP.
6. [`sbgms`](https://github.com/jmtomczak/intro_dgm/tree/main/sbgms): (i) an example of a score model using the score matching method and an MLP-based score model, (ii) an example of an SDE-based diffusion model parameterized by an MLP, (iii) an example of a conditional flow matching model parameterized by an MLP.
7. [`hybrid_modeling`](https://github.com/jmtomczak/intro_dgm/tree/main/hybrid_modeling): an example of a hybrid model using fully-connected layers and IDFs.
8. [`ebms`](https://github.com/jmtomczak/intro_dgm/tree/main/ebms): an example of an energy-based model parameterized by an MLP.
9. [`gans`](https://github.com/jmtomczak/intro_dgm/tree/main/gans): an example of a GAN parameterized by MLPs.
10. [`neural_compression`](https://github.com/jmtomczak/intro_dgm/tree/main/neural_compression): an example of applying deep generative modeling to image neural compression.
11. [`llms`](https://github.com/jmtomczak/intro_dgm/tree/main/llms): an example of a decoder-based transformer (an LLM; here we call it teenyGPT).


# Citation
If you use this code in any way, please refer to it by citing my book <a href="https://link.springer.com/book/10.1007/978-3-031-64087-2" target="_blank">"Deep Generative Modeling"</a>:
- APA style:
```
Tomczak, J. M. (2024). Deep Generative Modeling. Springer Cham
```
- Bibtex:
```
@book{tomczak2024deep,
  title={Deep Generative Modeling},
  author={Tomczak, Jakub M},
  publisher={Springer Cham},
  year={2024}
}
```
