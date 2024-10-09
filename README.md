Research Title: Stock Market Index Movement Prediction using Partial Contextual Embedding BERT-LSTM

Comparison of 4 parts:
1. Benchmark 1:        (X) fintuning BERT, (X) section, publication architecture  (Extra) use BERT sentiment
2. Benchmark 2:        (O) fintuning BERT, (X) section, publication architecture
3. Benchmark 3:        (X) fintuning BERT, (O) section, publication architecture  (Extra) use BERT sentiment
4. The Proposed Model: (O) fintuning BERT, (O) section, publication architecture

5. Benchmark 5:        (X) fintuning FinBERT, (X) section, publication architecture  (Extra) use FinBERT sentiment
6. Benchmark 6:        (O) fintuning FinBERT, (X) section, publication architecture
7. Benchmark 7:        (X) fintuning FinBERT, (O) section, publication architecture  (Extra) use FinBERT sentiment


Data

input_ids: input_ids from FinBERT
input_ids_bert: = input_ids from BERT (bert-base-uncased)
