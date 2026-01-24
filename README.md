# ViT from scratch
> Recreating the ViT (Vision Transformer) architecture from scratch using pytorch
<center>
<img src='https://github.com/Martinmbiro/ViT-from-scratch/raw/refs/heads/main/images/vit-paper-architecture-animation-full-architecture.gif' width=900 alt='vit-animation' />
</center>
<center>
Source: <a href='https://github.com/mrdbourke/pytorch-deep-learning/'>Pytorch deep learning</a>
</center>
</br></br>


Hello again 👋  
+ In this repository, I focus on repricating the ViT-Base variant of the Vision Transformer architecture proposed in the research paper: [An Image is Worth 16 x 16 words](https://www.wave.com/en/careers/job/5724891004/?source=LinkedIn)
+ The ViT is based on the Transformer architecture that was originally published in [Attention is all you need](https://arxiv.org/abs/1706.03762)
+ In the Jupyter notebook I repricate the four main equations underpinning the ViT architecture, using pytorch code. The pieces are then put together to form the ViT architecture
+ Detailed code and explanation are contained in the Jupyter notebook `01. ViT paper replication.ipynb` - feel free to open in Colab and explore

## The four equations:
These four equations represent the math behind the four major parts of the ViT architecture.
<center>
<img src='https://github.com/Martinmbiro/ViT-from-scratch/raw/refs/heads/main/images/mapping-the-four-equations-to-figure-1.png' alt='mapping equations to figure 1' />
</center>
<center>
Source: <a href='https://github.com/mrdbourke/pytorch-deep-learning/'>Pytorch deep learning</a>
</center>

## Tools ⚒️
**The tools used for this exercise are:**
1. [`Google Colab`](https://colab.google/) - A hosted _Jupyter Notebook_ service by Google.
2. [`PyTorch`](https://pytorch.org/) -  An open-source machine learning (ML) framework based on the Python programming language that is used for building **Deep Learning models**
3. [`numpy`](https://numpy.org/) - The fundamental package for scientific computing with Python
4. [`requests`](https://requests.readthedocs.io/en/latest/) - An elegant and simple HTTP library for Python

> _Notable modules from [The Python Standard Library](https://docs.python.org/3/library/index.html) include [`zipfile`](https://docs.python.org/3/library/zipfile.html) and [`pathlib`](https://docs.python.org/3/library/pathlib.html)_

## Reference 📚
+ [Dosovitskiy, A. (2020). An image is worth 16x16 words: Transformers for image recognition at scale. _arXiv preprint arXiv:2010.11929._](https://www.wave.com/en/careers/job/5724891004/?source=LinkedIn)
+ [Pytorch deep learning](https://github.com/mrdbourke/pytorch-deep-learning) by Daniel Bourke
