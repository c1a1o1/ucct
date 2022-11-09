# ucct
Unsupervised Class-to-Class Translation for domain variations


Abstract：Most image-to-image translation models tend to struggle in varying domain settings.
For one varying domain, samples vary greatly in shape and size and they have no
domain labels. In this paper, we propose an unsupervised class-to-class translation
model based on conditional contrastive learning to tackle the domain variations problem.
We assume that the latent modalities of two varying domains are categorizable by style
differences of different samples and turn the image-to-image translation problem into
class-to-class translation. This paper first performs unsupervised semantic clustering for
each domain to divide them into multiple classes and then leverages the classification
features of different classes to perform class-to-class translation. For each domain, we
propose two conditional contrastive learning loss functions to perform unsupervised
semantic clustering and decomposition it into multiple classes. Then in the class-to-class
translation stage, the classification features of different classes are employed to learn
the latent modalities. Employing the latent modalities of different classes, the proposed
model significantly outperforms state-of-the-art baseline methods。


Acknowlegement

Part of the code is borrowed from BalaGAN [https://github.com/orpatashnik/BalaGAN], DCL(https://github.com/chingyaoc/DCL).
