ArtSa — Thangka Mural Style Transfer
Thangka Mural Style Transfer Based on Artistic Style-Attentional Network and Two-stage Learning
Hang Lia, School of Information and Intelligent Transportation, Fujian Chuanzheng Communications College, Fuzhou 350007, China
Code Status — Code will be released upon acceptance
The complete implementation of this work is not yet public. It will be released on this
repository immediately upon acceptance of the manuscript in
Signal, Image and Video Processing.
We have chosen to release a complete and verified implementation rather than a partial
snapshot, as part of our development is still ongoing. This repository is reserved for that
release and will be updated accordingly.
What the public release will include
Item
Description
Training & inference code
Full pipeline for the ArtSA network, covering both stages of the two-stage learning strategy
Loss implementations
Adversarial loss and the two Thangka-specific regularization terms
Pre-trained weights
For our method, so that reported results can be reproduced without retraining
Evaluation scripts
Used to produce the perceptual metrics reported in the paper (SIFID / PSNR / SSIM)
User-study materials
The study interface, the anonymized raw response records of the 21-participant study, and the statistical scripts (standard deviation, Friedman, Holm-corrected Wilcoxon signed-rank)
Paper
Style transfer aims to apply the style features of one image to another. Thangka is a
traditional Tibetan painting form, and applying style transfer to Thangka can inject new
innovation into traditional art while preserving the core values and spirit of Thangka art.
Two challenges prevent existing methods from solving Thangka stylization: existing global
statistics and local patch-based methods suffer from unrealistic aesthetics and cannot
preserve content and style while capturing aesthetic information; and without adversarial
training, style control is coarse, producing images that are either monotonous or a mix of
styles. We propose an artistic style-attentional (ArtSA) network and a two-stage
learning strategy for Thangka style transfer.
Contributions
1. An artistic style-attentional (ArtSA) network that preserves content and style while
capturing aesthetic information in stylized Thangka images simultaneously.
2. A two-stage learning strategy that achieves fine-grained style control and prevents the
network from ignoring aesthetic signals, by adding adversarial training to traditional style
transfer.
Reproducibility
Even before the full implementation is released, the implementation details required to
reproduce the reported results are specified in full in the manuscript — including the
architecture of the attention module, the layer selections for the perceptual losses, the
stage-wise training schedules, the loss weights, the augmentation and cropping pipelines, and
all evaluation settings, together with the values of all hyper-parameters.
All comparisons in the paper were produced using the official pre-trained weights released
by the respective authors of each baseline method, under an identical evaluation pipeline.
Citation
If you find this work useful, please cite it. BibTeX will be added upon publication.
Contact
Hang Lia — School of Information and Intelligent Transportation, Fujian Chuanzheng Communications College, Fuzhou 350007, China
Keywords: style transfer, Thangka mural, style-attentional, adversarial training
