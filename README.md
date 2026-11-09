# Deep Learning and Neural Networks Course

Notebooks and slides for a 16-session course on deep learning with PyTorch. Each session is designed for a 90-minute class and has a Jupyter notebook for the hands-on part and a slide deck (PDF and PowerPoint) for the lecture. The explanations in the notebooks and slides are in Persian, with technical terms in English; all code is in English.

The course follows the companion [Machine Learning Course](https://github.com/keyvanmahmoudi/Machine_Learning_Course): sessions 1 and 2 build neural networks from scratch with NumPy, session 3 introduces PyTorch, and the rest of the course covers training, convolutional networks, sequence models, Transformers and generative models.

## Contents

| # | Session | Topics | Data | Slides |
|---|---|---|---|---|
| 1 | [From ML to deep learning: Perceptron and MLP](01.%20Perceptron_and_MLP.ipynb) | Artificial neuron, perceptron learning rule, XOR, activation functions, MLP forward pass, universal approximation | Synthetic | [PDF](slides/01.%20Perceptron_and_MLP.pdf) · [PPTX](slides/01.%20Perceptron_and_MLP.pptx) |
| 2 | [Backpropagation and gradient descent from scratch](02.%20Backpropagation_and_Gradient_Descent.ipynb) | Loss functions, gradient descent, computational graphs, a tiny autograd engine, matrix backprop, gradient checking, vanishing gradients | `make_moons` | [PDF](slides/02.%20Backpropagation_and_Gradient_Descent.pdf) · [PPTX](slides/02.%20Backpropagation_and_Gradient_Descent.pptx) |
| 3 | [PyTorch fundamentals](03.%20PyTorch_Fundamentals.ipynb) | Tensors, reshaping, broadcasting, NumPy bridge, GPU, autograd, `nn.Linear` and `torch.optim` | Synthetic | [PDF](slides/03.%20PyTorch_Fundamentals.pdf) · [PPTX](slides/03.%20PyTorch_Fundamentals.pptx) |
| 4 | [The standard training loop](04.%20Training_Loop_FashionMNIST.ipynb) | `Dataset`, `DataLoader`, `nn.Module`, train/validation/test split, `train_one_epoch`/`evaluate`, confusion matrix, saving models | Fashion-MNIST | [PDF](slides/04.%20Training_Loop_FashionMNIST.pdf) · [PPTX](slides/04.%20Training_Loop_FashionMNIST.pptx) |
| 5 | [Optimization](05.%20Optimization.ipynb) | SGD, momentum, RMSprop, Adam/AdamW, learning-rate schedules, weight initialization | Fashion-MNIST | [PDF](slides/05.%20Optimization.pdf) · [PPTX](slides/05.%20Optimization.pptx) |
| 6 | [Regularization and normalization](06.%20Regularization_and_Normalization.ipynb) | Overfitting, weight decay, dropout, batch normalization, early stopping, data augmentation | Fashion-MNIST | [PDF](slides/06.%20Regularization_and_Normalization.pdf) · [PPTX](slides/06.%20Regularization_and_Normalization.pptx) |
| 7 | [Convolutional neural networks](07.%20Convolutional_Neural_Networks.ipynb) | Convolution, padding, stride, pooling, receptive field, feature maps, a CNN for image classification | Fashion-MNIST, CIFAR-10 | [PDF](slides/07.%20Convolutional_Neural_Networks.pdf) · [PPTX](slides/07.%20Convolutional_Neural_Networks.pptx) |
| 8 | [Modern CNN architectures](08.%20Modern_CNN_Architectures.ipynb) | LeNet, AlexNet, VGG, residual connections, ResNet from scratch | CIFAR-10 | [PDF](slides/08.%20Modern_CNN_Architectures.pdf) · [PPTX](slides/08.%20Modern_CNN_Architectures.pptx) |
| 9 | [Transfer learning and fine-tuning](09.%20Transfer_Learning.ipynb) | Pretrained ImageNet models, feature extraction vs. fine-tuning, `torchvision.models` | Oxford Flowers-102 | [PDF](slides/09.%20Transfer_Learning.pdf) · [PPTX](slides/09.%20Transfer_Learning.pptx) |
| 10 | Recurrent neural networks | Sequence data, RNN cell from scratch, backpropagation through time, exploding gradients, time-series forecasting | Synthetic time series | *in preparation* |
| 11 | [LSTM, GRU and word embeddings](11.%20LSTM_GRU_Text_Classification.ipynb) | Gating, tokenization, vocabularies, `nn.Embedding`, padding and packing, sentiment classification | IMDB | [PDF](slides/11.%20LSTM_GRU_Text_Classification.pdf) · [PPTX](slides/11.%20LSTM_GRU_Text_Classification.pptx) |
| 12 | [Sequence-to-sequence models and attention](12.%20Seq2Seq_and_Attention.ipynb) | Encoder–decoder, teacher forcing, Bahdanau attention, attention maps | Synthetic date translation | [PDF](slides/12.%20Seq2Seq_and_Attention.pdf) · [PPTX](slides/12.%20Seq2Seq_and_Attention.pptx) |
| 13 | [The Transformer from scratch](13.%20Transformer_from_Scratch.ipynb) | Scaled dot-product and multi-head attention, positional encoding, a character-level GPT | Tiny Shakespeare | [PDF](slides/13.%20Transformer_from_Scratch.pdf) · [PPTX](slides/13.%20Transformer_from_Scratch.pptx) |
| 14 | [Pretrained Transformers with Hugging Face](14.%20Hugging_Face_Transformers.ipynb) | Tokenizers, pipelines, fine-tuning a BERT model on Persian text | Persian sentiment | [PDF](slides/14.%20Hugging_Face_Transformers.pdf) · [PPTX](slides/14.%20Hugging_Face_Transformers.pptx) |
| 15 | Autoencoders and variational autoencoders | Undercomplete and denoising autoencoders, latent spaces, the reparameterization trick, VAE | Fashion-MNIST | *in preparation* |
| 16 | GANs, diffusion and the final project | DCGAN, training dynamics, denoising diffusion (DDPM) on 2-D data, final project guidelines | Fashion-MNIST, synthetic | *in preparation* |

Datasets are downloaded automatically by the notebooks (through `torchvision`, `datasets` or a direct link), so no data files are stored in this repository.

## Getting started

Every notebook has an **Open in Colab** badge at the top. Colab already has PyTorch installed; for the sessions that train convolutional networks or Transformers, switch the runtime to a GPU (`Runtime → Change runtime type → T4 GPU`).

To run locally:

```bash
git clone https://github.com/keyvanmahmoudi/Deep_Learning_Course.git
cd Deep_Learning_Course
pip install torch torchvision numpy matplotlib scikit-learn jupyter
jupyter notebook
```

Install PyTorch with the command for your platform and CUDA version from [pytorch.org](https://pytorch.org/get-started/locally/). Sessions 11 and 14 also need `pip install datasets transformers`.

## Slides

The slides use the free [Vazirmatn](https://github.com/rastikerdar/vazirmatn) font. The PDF files display correctly everywhere; to edit the PowerPoint files, install Vazirmatn first.

## Prerequisites

Python, NumPy and the material of the [Machine Learning Course](https://github.com/keyvanmahmoudi/Machine_Learning_Course): train/test splits, feature scaling, overfitting, and classification metrics. Basic calculus (derivatives and the chain rule) and linear algebra (matrix multiplication) are used from session 2 onwards.

## Author

**Keyvan Mahmoudi**, PhD student in computer engineering, University of Tehran
[LinkedIn](https://www.linkedin.com/in/keyvan-mahmoudi-7b3280103) · [Hugging Face](https://huggingface.co/KeyvanMahmoudi)

## License

The code in this repository is released under the [MIT License](LICENSE). The slides and notebook text may be used for teaching with attribution.
