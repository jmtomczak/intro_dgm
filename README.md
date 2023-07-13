# <a href="https://link.springer.com/book/10.1007/978-3-030-93158-2">"Deep Generative Modeling"</a>: Introductory Examples

This repository contains examples of deep generative models for the book <a href="https://link.springer.com/book/10.1007/978-3-030-93158-2">"Deep Generative Modeling"</a>:
1. Autoregressive Models (ARMs): ARMs parameterized with Causal Convolutionas and Transformers
2. Flow-based models (flows): RealNVP and IDFs (Integer Discrete Flows)
3. Variational Auto-Encoders (VAEs): a plain VAE and various priors, a hierarchical VAE
4. Diffusion-based Deep Generative Models (DDGMs): a Gaussian forward diffusion
5. Hybrid modeling
6. Energy-based Models
7. Generative Adversarial Networks (GANs)
8. Neural Compression with Deep Generative Modeling

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
1. `arms`: an example of an autoregressive model with a causal convolutiona layer in 1D and transformers.
2. `flows`: an example of a flow-based model, namely, RealNVP with coupling layers and permutation layers, and IDFs (Integer Discrete Flows).
3. `vaes`: an example of a Variational Auto-Encoder using fully-connected layers and a standard Gaussian prior, and another example of various priors for VAEs, and a third example on a hierarchical VAE.
4. `ddgms`: an example of a Diffusion-based Deep Generative Model using the a Gaussian forward diffusion with a fixed variace and a reverse diffusion parameterized by MLPs.
5. `hybrid_modeling`: an example of a hybrid model using fully-connected layers and IDFs.
6. `ebms`: an example of an energy-based model parameterized by an MLP.
7. `gans`: an example of a GAN parameterized by MLPs.
8. `neural_compression`: an example of applying deep generative modeling to image neural compression.


# Citation
If you use this code in any way, please refer to it by citing my book <a href="https://link.springer.com/book/10.1007/978-3-030-93158-2">"Deep Generative Modeling"</a>:
- APA style:
```
Tomczak, J. M. (2022). Deep Generative Modeling. Springer Nature
```
- Bibtex:
```
@book{tomczak2022deep,
  title={Deep Generative Modeling},
  author={Tomczak, Jakub M},
  publisher={Springer Nature},
  year={2022}
}
```
