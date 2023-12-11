<div align="center">

# **🎏 k-Distribution 🎏**

</div>

Source for the article: [k* Distribution: Evaluating the Latent Space of Deep Neural Networks using Local Neighborhood Analysis](https://arxiv.org/abs/2312.04024)

## 🌟 Features

- Identification of various distribution patterns of samples in the latent space based on neighborhood characteristics
- A model-agnostic latent space analysis of neural networks, focusing on samples from a single class
- A method for straightforwardly comparing different classes and understanding how samples from various classes are distributed in the learned latent space

<div align="center">
    <img src="./assets/ResNet-IN-IN_16-Base-Test-distribution-1.png" alt="" width="45%", style="background-color:white">
    <img src="./assets/ResNet-IN-IN_16-Base-Test-distribution-2.png" alt="" width="45.72%", style="background-color:white">
</div>
Visualization of the distribution of samples in latent space using, k* distribution of all classes of 16-class-ImageNet for the Logit Layer of ResNet-50 Architecture.

## 📝 Citation

If you find this project useful please cite:

```
@article{kotyan2024kdistribution,
    title = {k* {{Distribution}}: {{Evaluating}} the {{Latent Space}} of {{Deep Neural Networks}} Using {{Local Neighborhood Analysis}}},
    shorttitle = {k* {{Distribution}}},
    author = {Kotyan, Shashank and Tatsuya, Ueda and Vargas, Danilo Vasconcellos},
    year = {2023},
    month = dec,
    number = {arXiv:2312.04024},
    eprint = {2312.04024},
    publisher = {{arXiv}},
    doi = {10.48550/arXiv.2312.04024},
}
```