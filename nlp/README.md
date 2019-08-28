### 自然语言处理岗常见面试题

#### 问题1：CRF反向求导

#### 问题2：CTC, beam-search

#### 问题3：LSTM的结构以及为什么可以改善梯度消失

#### 问题4：Transformer

#### 问题5：Transformer-XL 

#### 问题6: Word2vec, Glove, fasttext, Bert, XLNet
[BERT在各领域的应用](https://blog.csdn.net/enohtzvqijxo00atz3y8/article/details/92256140)
GPT 等普通语言模型的训练目标是 Causal Language Model，BERT 的训练目标是 MLM，在此基础上通过改进 mask 又有了 Whole Word Masking/N-gram Masking/ERNIE 等目标。把 Transformer 的 encoder 和 decoder 都用上可以得到 MASS，双语平行语料预训练可以用 TLM。XLNet的训练目标是PLM.
