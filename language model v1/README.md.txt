## RNN Language Model

- Task: Next-word prediction
- Architecture: Embedding → SimpleRNN → Dense
- Observations:
  - A lot of unk generation
  - Poor long-term memory


## GRU & LSTM Language Model

- Task: Next-word prediction
- Architecture: Embedding → GRU & LSTM → Dense
- Observations:
  - Longer Memory 
  - Unk generation decreased
  - New problem : repetition