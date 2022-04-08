# NLP_models_benchmarking

The purpose of this project is to compare and analyze the performance of different models in Text classification.

An IMDB dataset was used to train below models,

1. Conv layer based model
2. Bidirectional LSTM
3. Transformer based model

It’s already known that the transformer can outperform other two in a given NLP task. This project gives us the metrics that can help in better understanding of this statement.

The accuracies achieved by these models during training are tabulated below.
|Models| val_loss | val_accuracy | Time taken to train(s) |
|--|--|--|--|
|Conv| 0.9130| 0.8398|53 |
|Bidirectional LSTM| 0.4632|0.8576 |615 |
|Transformer| 0.3237| 0.8674| 97|


From the above table, the transformer model seems to prevail over the other two with a considerable difference in the performance. Even though the accuracy of the bidirectional LSTM is closer to transformer's accuracy, the time taken to train a bidirectional LSTM is high making it unreliable.
