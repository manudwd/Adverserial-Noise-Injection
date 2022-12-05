# Adverserial-Noise-Injection

The process of adding noise from $\mathcal{Ν}(𝜇,𝜎^2)$ over the training process becomes too stable, and often only lead to improvement in robustness of models with large complexity.

We can model this noise as an adversary, and a defender that tries to reduce the noise.

Non-zero sum game, in discrete two player simultaneous play.

The choice of function is affine in the first term, concave in the second, convex in the third.

The feasible saddle point of this function is known, and it exists in the margin of tolerance of the model such that if 
\$J(\gamma^{\star},\sigma^{\star})$ is played, model behavior can be approximated  to a $\mathcal{N}(0,1)$ noise injection model. 

## Lemke-Howson Algorithm

Is used to compute a Nash Equilibrium.

## Results

![image](https://user-images.githubusercontent.com/56117150/205672680-1d13044a-cedc-4a06-b5e0-42f53d4316c3.png)
