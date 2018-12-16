# <center> ManGAN </center>

<center> <b>Warning:</b> Work still in Progress ¯\_(ツ)_/¯ </center>

Assisting Colorization of Manga Characters Concept Art using Conditional GAN

**Abstract:** Colorization is a challenging task that has recently been tackled by deep learning. Line art colorization is particularly difficult because there is no grayscale value to indicate the color intensities as there is in black-and-white photograph images. When designing a character, concept artists often need to try different color schemes, however, colorization is a time-consuming task. In this article, we propose a semi-automatic framework for colorizing manga concept arts by letting concept artists try different color schemes and obtain colorized results in fashion time. Our approach uses Conditional Generative Adversarial Networks (cGAN) and outperforms current hint-based line-art colorization techniques by providing natural-looking arts with only minor coloring mistakes.



## The Architecture and Training

![logos](https://github.com/Lodur03/ManGAN/blob/master/gen-disc.png?raw=true)

To improve the results made by architecture, some strategies were adopted:
- Leaky ReLUs
- Residual Connections
- Batch Normalization
- One-sided Label Smoothing

# The results

![logos](https://github.com/Lodur03/ManGAN/blob/master/1.jpg?raw=true)
