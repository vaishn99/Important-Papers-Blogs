# Important papers and blogs on Generative modelling 


## classical generative model :<br/>

1. https://cs229.stanford.edu/notes2021fall/cs229-notes8.pdf (Note on EM Algoithm,ELBO maximisation from stanford)<br/>
2. https://youtu.be/LmpkKwsyQj4 (Anant Avati's lecture on K-means--> GMM-->>EM algorithm,A Must watch)<br/>
3. https://cs229.stanford.edu/summer2019/cs229-notes9.pdf (Factor analysis (A latent space model) lecture notes).<br/>
4. https://www.countbayesie.com/blog/2017/5/9/kullback-leibler-divergence-explained(A good blog that explains about KL Divergence)<br/>
5. https://stillbreeze.github.io/Variational-Inference-and-Expectation-Maximization/ (On Expectation Maximization)


## Vanilla VAE :

1. http://stillbreeze.github.io/Variational-Inference-and-
Expectation-Maximization/
2. https://www.cs.cmu.edu/~tom/10-702/Zoubin-702.pdf
3. https://arxiv.org/pdf/1312.6114.pdf (VAE base paper)
4. https://arxiv.org/pdf/1606.05908.pdf (A tutorial on Variational Auto-Encoder)
5. https://gregorygundersen.com/blog/2018/04/29/
reparameterization/(A really good blog on reparametrisation)
6. http://approximateinference.org/accepted/HoffmanJohnson2016.pdf 
(**ELBO** **Paper**)


## Some of the important extensions over Vanilla VAE:

1. https://openreview.net/references/pdf?id=Sy2fzU9gl (Beta -VAE base paper)
2. https://arxiv.org/pdf/1804.03599.pdf (discusses about dissentanglement in Beta-VAE)
3. https://arxiv.org/pdf/1706.02262.pdf (Info- VAE)
4. https://arxiv.org/abs/1705.07120 (VAE with vamp Prior)
5. https://ml.berkeley.edu/blog/posts/vq-vae/ (Vector quantised VAE)

## 





## Matrix completion approach(Classical): SVD,CUR,PQ
1. Good paper on randomised SVD (recent) : https://arxiv.org/pdf/1608.02148.pdf
2. CUR decomposition Base paper : https://www.pnas.org/doi/full/10.1073/pnas.0803205106 <br/>
3. Good material for understanding CUR better (recent) : https://arxiv.org/abs/1907.12668 <br/>
4. PQ Decomposition blog : https://towardsdatascience.com/recommendation-system-matrix-factorization-d61978660b4b <br/>
5. Stanford mini lecture(inside a playlist) : https://youtu.be/SO1KTzuKTSI <br/>

## Neural Collaborative Filtering(NCF,Deep learning based): <br/>

1.  NCF base paper : https://arxiv.org/pdf/1708.05031.pdf

## Some blogs that I followed (Will make life easier)

- https://jxmo.io/posts/nce (On NCE) <br/>
- https://github.com/eugeneyan () <br/>
- https://eugeneyan.com/writing/bandits/ <br/>
- https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/tutorial8/Deep_Energy_Models.html
- https://www.robots.ox.ac.uk/~ojw/files/NotesOnCD.pdf (On Contrastive Divergence)
- https://timvieira.github.io/blog/post/2014/12/21/importance-sampling/ (On importance sampling)
- https://timvieira.github.io/blog/post/2016/12/19/counterfactual-reasoning-and-learning-from-logged-data/ (off-policy)
- https://web.archive.org/web/20170401030417/http://www.columbia.edu/~mh2078/MCS04/MCS_var_red2.pdf(Variance reduction techniques)
- https://jonathan-hui.medium.com/gan-why-it-is-so-hard-to-train-generative-advisory-networks-819a86b3750b
    (Really good blog that portraits the usefulness of JS divergence(Vanilla GAN) instead of KL divergence(VAE) )


# Important papers on GAN


- Generative Adversarial Networks(https://arxiv.org/abs/1406.2661)
- Adversarial Feature Learning(https://arxiv.org/abs/1605.09782)
- DC-GAN (https://arxiv.org/abs/1511.06434)
- GAN vs Actor Critic (https://www.quora.com/How-is-the-GAN-different-from-the-actor-critic-method-in-reinforcement-learning)
- Modifying naive GAN training(Alternative GD) procedure.Many papers got published in ICLR-2016,2017,2018 proposing various other training procedure.This is the paper that introduces issues like modal collapse (https://arxiv.org/pdf/1611.02163.pdf)
- Chekhov GAN-offeres a game theortic inspired approach for training the GAN. (https://arxiv.org/pdf/1706.03269.pdf?).
- Link to a preesentation slides made by me on the chekhov GAN.(https://docs.google.com/presentation/d/1NdsimG3mRsrfH6hH3O4PYxbOllFjxRlobkD09a8GoJU/edit?usp=sharing)


# Score-Based models:

Will be updated soon ... 

# Energy Based models:

Will be updated soon ... 

# Diffusion models:

- Understanding Diffusion Models: A Unified Perspective:An important paper that connects VAE to diffusion through Heirarchical VAE . (https://arxiv.org/abs/2208.11970)
