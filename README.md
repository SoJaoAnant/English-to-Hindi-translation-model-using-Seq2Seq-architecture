# Seq2Seq encoder decoder model with attention
### For translating english sentences to hindi

this is a model that implements the encoder decoder and attention architecture to later combine into a seq2seq model.
the model uses the [IITB English to Hindi parallel Corpus](https://www.cfilt.iitb.ac.in/iitb_parallel/) which contains around 1.5 millilon parallel english and hindi sentences.

## The models

-  1 - [Seq2Seq model using LSTM](English-to-Hindi-translation-model-using-Seq2Seq-architecture\seq2seq LSTM\seq2seq_lstm_eng2hin.ipynb)

![the training loss](English-to-Hindi-translation-model-using-Seq2Seq-architecture\seq2seq LSTM\enhi_lstm_training_loss.png)

-  2 - [Seq2Seq model using GRU](English-to-Hindi-translation-model-using-Seq2Seq-architecture\seq2seq GRU\seq2seq_gru_eng2hin.ipynb)

![the training loss](English-to-Hindi-translation-model-using-Seq2Seq-architecture\seq2seq GRU\enhi_gru_training_loss.png)

-  3 - [Seq2Seq model with Attention](English-to-Hindi-translation-model-using-Seq2Seq-architecture\seq2seq Attention\seq2seq-attention-en2hi.ipynb)
-  
![the training loss](English-to-Hindi-translation-model-using-Seq2Seq-architecture\seq2seq Attention\enhi_attn_loss.png)

you can find the trained model's dictionaries [here](https://drive.google.com/drive/folders/1vD4-hJpIAdNLYt41rw_9MRIEfCecdFYd?usp=sharing)

## References

https://github.com/bentrevett/pytorch-seq2seq
[Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215)
[Attention Is All You Need](https://arxiv.org/abs/1706.03762)