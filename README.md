# try_gcn
compare node2vec, gcn, gat on word context graph for word embeddings.

尝试使用GCN做词向量。没有node2vec效果好，但是比随机的好。然后又做了GAT，比GCN拟合慢，而且容易进入平原。

嵌入方法:
1. 完全随机的参数。（GCN)
2. 监督预测结巴词性。(GCN,GAT)
3. 监督预测（skip-gram）词上下文。(GCN,GAT)
