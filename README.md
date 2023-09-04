# Application of Compact Convolutional Transformers (CCTs)

<div style='float:left;'>
  <img href='' src='https://img.shields.io/badge/Maintained%3F-Yes-brightgreen.svg' style='margin-right:10px;'>
  <img href='https://www.python.org/' src='https://img.shields.io/badge/Made with-Python-blue' style='margin-right:10px;'>
  <img href='https://choosealicense.com/licenses/mit/' src='https://img.shields.io/badge/LICENSE-MIT-green' style='margin-right:10px'>
  <img href='https://github.com/MatthewJansen/Application-of-CCT' src='https://img.shields.io/github/stars/MatthewJansen/Application-of-CCT?style=social' style='margin-right:10px'>
  <img href='https://github.com/MatthewJansen/Application-of-CCT/fork' src='https://img.shields.io/github/forks/MatthewJansen/Application-of-CCT?style=social' style='margin-right:10px'>
  <img href='https://github.com/MatthewJansen/Application-of-CCT' src='https://img.shields.io/github/watchers/MatthewJansen/Application-of-CCT?style=social' style='margin-right:10px'>  
</div>


<center>
    <figure>
        <img src="https://production-media.paperswithcode.com/methods/cct_sBBD6Sv.png" alt ="Skin Cancer" style='width:70%;'>
        <figcaption>
            Image Source: <a href="https://paperswithcode.com/method/cct">PapersWithCode | Compact Convolutional Transformers</a>
        </figcaption>
    </figure>
</center>

<br>

## 📄 Overview
In recent years, Transformers have become the go-to for Natural Language Processing (NLP) and have been used in research for Computer Vision and Time Series Forecasting to make groundbreaking discoveries.

There is a clear association between the increasing number of trainable parameters in models and the progress made in these domains, and many researchers may believe this is due to the inability of transformers to adapt to small datasets.

The Compact Convolutional Transformer approach introduced in the paper "Escaping the Big Data Paradigm with Compact Transformers" addresses the issues with Transformer models on small datasets. 

The CCT architecture aims to increase performance and provide flexibility for input image sizes whilst demonstrating the independence of Positional Embedding in contrast to other transformer-based architectures. The utilization of the CCT architecture empowers researchers to achieve noteworthy results despite having restricted trainable parameters, small datasets, and a single processing unit, be it a GPU or a CPU.

<center>
    <figure>
        <img src="https://i.postimg.cc/wj0FdNkN/CCT.png" alt ="CCT (Diagram)" style='width:100%;'>
        <figcaption>
            Image Source: <a href="https://paperswithcode.com/method/cct">PapersWithCode | Compact Convolutional Transformers</a>
        </figcaption>
    </figure>
</center>

<br>
<br>

This notebook aims to provide a comprehensive guide on how to implement and train a CCT model that is specifically designed for classifying skin cancer. The model will accurately identify potential skin cancer cases, which will promote early intervention and improve patient outcomes.

**For more information on the Compact Convolutional Transformer architectures and Transformers in general, please refer to the following links:**
> - CCT Paper: [Escaping the Big Data Paradigm with Compact Transformers](https://arxiv.org/abs/2104.05704v4)
> - Vision Transformer Paper: [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale (2021)](https://arxiv.org/pdf/2010.11929.pdf)
> - Attention Mechanism Paper: [Attention Is All You Need (2017)](https://arxiv.org/pdf/1706.03762.pdf)
> - V7Labs Article: [Vision Transformer: What It Is & How It Works [2023 Guide]](https://www.v7labs.com/blog/vision-transformer-guide)
> - Viso.ai Article: [Vision Transformers (ViT) in Image Recognition – 2022 Guide](https://viso.ai/deep-learning/vision-transformer-vit/)

<br>

## 📁 Dataset

The dataset used in this notebook is known as the International Skin Imaging Collaboration (ISIC) Skin Cancer Detection Dataset. The ISIC is an academia and industry partnership designed to facilitate the application of digital skin imaging to help reduce melanoma mortality. This notebook uses the Kaggle version of this dataset.

**For more information check the following:**
> - [Kaggle Dataset](https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign)
> - [The International Skin Imaging Collaboration](https://www.isic-archive.com/#!/topWithHeader/wideContentTop/main)

<br>

## Requirements

- **Recommended python version:** Python +3.8.10 64-bit

[Please note that this section will be updated in due course.]

## Project Structure

```
.
├── LICENSE
├── README.md
└── application-of-compact-convolutional-transformers.ipynb
```

- **LICENSE** | project license (MIT)
- **README.md** | project readme file
- **application-of-compact-convolutional-transformers.ipynb** | project notebook


## Usage
`See application-of-compact-convolutional-transformers.ipynb`

## License
This project is licensed under the terms and conditions of the [MIT license](https://choosealicense.com/licenses/mit/).
