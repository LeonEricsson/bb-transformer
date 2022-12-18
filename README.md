# NLP

This is a collection of various personal projects related to NLP. 

### **autogen**

Auto-regressive generator which takes a text file as input, where each line is assumed to be a training example, and generates new examples of similar type. Under the hood it's a auto-regressive character-level language model, with a wide choice of models. For example one could feed the model a list of names and it would generate ideas for new ones. This project is purely educational and was originally designed to give me a foundational understanding of the NLP field, specifically language and auto-regressive models. 

Currently supported models:

* bigram, following [Daniel Jurafsky & James H. Martin 2021](https://web.stanford.edu/~jurafsky/slp3/3.pdf)
* MLP, following [Bengio et al. 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)
* CNN, following [DeepMind WaveNet 2016](https://arxiv.org/abs/1609.03499)

Future models:

* RNN, following [Mikolov et al. 2010](https://www.fit.vutbr.cz/research/groups/speech/publi/2010/mikolov_interspeech2010_IS100722.pdf)
* LSTM, following [Graves et al. 2014](https://arxiv.org/abs/1308.0850)
* GRU, following [Kyunghyun Cho et al. 2014](https://arxiv.org/abs/1409.1259)
* Transformer, following [Vaswani et al. 2017](https://arxiv.org/abs/1706.03762)

This project is inspired by Andrej Karpathy.

### **transformer**

Bare-bones implementation of the transformer architecture, as spelled out by Vaswani et al. in the already classic paper [**Attention is all you need**](https://arxiv.org/abs/1706.03762). Nothing fancy about the implementation, I ran through the design strictly as an exercise tool to build deeper understanding of the architecture. Fully implemented as custom PyTorch modules.  