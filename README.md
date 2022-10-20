# Awesome Deep Learning

## Enhancements

:star: [pdf](https://arxiv.org/pdf/1502.03167.pdf) Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift 2015 @ Ioffe, Szegedy

## Sequence Processing (NLP, Time Series)


[pdf](https://arxiv.org/pdf/1810.04805.pdf) BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding 2019 @ Delvin et al
- Transformer-based architecture.

:star: [pdf](https://arxiv.org/pdf/1706.03762.pdf) Attention Is All You Need 2017 @ Vaswani et al
- Experiments on two machine translation tasks show these models to be superior in quality while being more parallelizable and requiring significantly less time to train.
- The encoder is composed of a stack of N = 6 identical layers. Each layer has two sub-layers. The first is a multi-head self-attention mechanism, the second is a positionwise fully connected. Residual connection around each of the two sub-layers, followed by layer normalization.
That is, the output of each sub-layer is LayerNorm(x + Sublayer(x)). To facilitate residual connections, all layers in the model, produce outputs of dimension model = 512.
