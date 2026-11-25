# Evidential Uncertainty-Guided Boundary Project Page

Project page for "Exploring the Connection Between Uncertainty and Tissue Boundaries in Medical Image Segmentation"

Authors: Na Zeng, Qiao Lin, Xingyue Wang, Jiang Liu, Jonathan M. Garibaldi

Affiliations: University of Nottingham Ningbo China; Southern University of Science and Technology

## Abstract
Automatic medical image segmentation, as a prerequisite for clinical quantitative analysis, forms the basis of computer-aided diagnosis. However, blurry object boundaries caused by factors such as imaging quality and inherent physiological properties of tissues or lesions are the main causes of imprecise segmentation. This aligns with the common understanding that high uncertainty and misclassification tend to occur at boundaries in segmentation. To address the challenge, we investigate this phenomenon and explore the connection between uncertainty and tissue boundaries by analysing various tissues. Then an Evidential Uncertainty-Guided Boundary (EUGB) loss is further proposed to demonstrate that uncertainty information can indeed facilitate combating boundary segmentation errors. The proposed EUGB loss not only emphasizes challenging pixels along blurry boundaries using evidential uncertainty, but also introduces a regularization term that constrains uncertainty learning by penalizing incorrect predictions and reinforcing correct ones. The effectiveness of the proposed EUGB loss is verified in the public LIDC-IDRI, ISIC 2018, and OCTA-500 datasets with two classic medical image segmentation networks (U-Net and TransU-Net). Experimental results demonstrate that the proposed loss outperforms seven other segmentation loss functions in terms of boundary segmentation, while maintaining competitive region-level segmentation accuracy. Beyond introducing a new loss function, this paper provides empirical insights for selecting appropriate loss functions across different application scenarios. We systematically analyze the strengths and limitations of existing losses from multiple perspectives, including reliability and dataset characteristics. This analysis offers practical insights that enable researchers and practitioners to optimize segmentation performance based on specific data attributes.

## Usage

Open index.html in a web browser, or visit the deployed GitHub Pages site.

## Code

Coming soon!

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
