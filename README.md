# Density Estimation with Gaussian Mixture Models

Deck 11 of the [Mathematics for Machine Learning &mdash; Companion Series](https://github.com/BrendanJamesLynskey/MML_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/MML_11_Gaussian_Mixture_Models/

Mixture model likelihood, the EM algorithm derived from the latent-variable
view, responsibilities, the lower bound, soft vs hard clustering, and
model-order selection. Interactive 2D EM animator with step-by-step
E and M passes.

## What's inside

- Why a single Gaussian isn't enough &mdash; multi-modal data
- The mixture model: weights, components, latent assignments
- The likelihood and why direct maximisation is hard
- The latent-variable view: $z_n$ as a categorical
- The EM algorithm derived from a variational lower bound
- Responsibilities and how they generalise $k$-means
- M-step formulae for means, covariances and mixing weights
- Initialisation, local optima and convergence behaviour
- Model-order selection: BIC, marginal likelihood
- Interactive: step EM on a 2D mixture and watch the responsibilities flow

Companion to chapter 11 of:

> Deisenroth, M. P., Faisal, A. A. &amp; Ong, C. S. (2020). *Mathematics for Machine Learning.* Cambridge University Press. Free PDF: [mml-book.github.io](https://mml-book.github.io/).

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
