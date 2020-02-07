# Flood-Filling Networks

![](https://3.bp.blogspot.com/-gaOWX7BKxMg/W0t7BBsWN-I/AAAAAAAADKs/l25qFCT1pK0MRRKXYppnHqQTu6OQdGnfQCLcBGAs/s1600/image4.gif)

https://ai.googleblog.com/2018/07/improving-connectomics-by-order-of.html


FFNs have been very successful for Google on dense volumetric EM data. Wonder if it could be adopted to brightfield.

This issue is being tracked on GitHub as [#73](https://github.com/reconstrue/brightfield_on_colab/issues/73).

Code (Apache-2.0 licensed) code was taken from Google's 
repro: [ffn_inference_demo.ipynb](https://github.com/google/ffn/blob/master/ffn_inference_demo.ipynb) and
used here to seed probing if it could be run on Colab.

## Future work
Start here: [VAE output to train FFN](https://github.com/hasagar97/Flood-Filling-Networks) supposedly rather easy.
![Screen Shot 2019-12-02 at 13 35 15](https://user-images.githubusercontent.com/473077/69997289-a297cb00-1508-11ea-98b6-6ced55ebf774.png)

That would reduce training costs.

## References

### Code
- Main repo: https://github.com/google/ffn 
  - (Apache-2.0)

### Papers
- First paper: [FFNs](https://arxiv.org/pdf/1611.00421.pdf)
- Main (later?) paper:
  - pre nature pre-print: [High-Precision​​Automated​​Reconstruction​​of​​Neurons​​with​​Flood-filling​​Networks](https://www.biorxiv.org/content/10.1101/200675v1.full.pdf)
  - [Nature article](https://www.nature.com/articles/s41592-018-0049-4)
- Pre-prints: 
  - FFN [High-precision automated reconstruction of neurons with flood-filling networks](https://www.ncbi.nlm.nih.gov/pubmed/30013046)
  - SECGAN: [Segmentation-Enhanced CycleGAN](https://www.biorxiv.org/content/biorxiv/early/2019/02/13/548081.full.pdf)
  - CMN: [Learning cellular morphology with neural networks](https://www.biorxiv.org/content/10.1101/364034v2)

- P
- Blog post [Improving Connectomics by an Order of Magnitude](https://ai.googleblog.com/2018/07/improving-connectomics-by-order-of.html) from Google AI blog
- [Flood-Filling Networks, from Google AI research papers](https://ai.google/research/pubs/pub45815/)
- [Automated Reconstruction of a Serial-Section EM Drosophila Brain with Flood-Filling Networks and Local Realignment](https://fafb-ffn1.storage.googleapis.com/landing.html)









