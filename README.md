# <a href="https://link.springer.com/book/10.1007/978-3-030-93158-2">"Deep Generative Modeling"</a>: Introductory Examples

This repository contains examples of deep generative models for the book <a href="https://link.springer.com/book/10.1007/978-3-030-93158-2">"Deep Generative Modeling"</a>:
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
1. `mog`: an example of a mixture of Gaussians with equiprobable components or trainable component probabilities. 
2. `arms`: an example of an autoregressive model with a causal convolutiona layer in 1D and transformers.
3. `flows`: an example of a flow-based model, namely, RealNVP with coupling layers and permutation layers, and IDFs (Integer Discrete Flows).
4. `vaes`: (i) an example of a Variational Auto-Encoder using fully-connected layers and a standard Gaussian prior, (ii) an example of various priors for VAEs, (iii) an example of a hierarchical VAE.
5. `ddgms`: an example of a Diffusion-based Deep Generative Model using a Gaussian forward diffusion with a fixed variace and a reverse diffusion parameterized by an MLP.
6. `sbgms`: (i) an example of a score model using the score matching method and an MLP-based score model, (ii) an example of an SDE-based diffusion model parameterized by an MLP, (iii) an example of a conditional flow matching model parameterized by an MLP.
7. `hybrid_modeling`: an example of a hybrid model using fully-connected layers and IDFs.
8. `ebms`: an example of an energy-based model parameterized by an MLP.
9. `gans`: an example of a GAN parameterized by MLPs.
10. `neural_compression`: an example of applying deep generative modeling to image neural compression.
11. `llms`: an example of a decoder-based transformer (an LLM; here we call it teenyGPT.


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
