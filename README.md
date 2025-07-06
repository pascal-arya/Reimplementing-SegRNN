# Reimplementing SegRNN—RNN that better at Long-Term Time Series Forcasting—Paper
![image](https://github.com/user-attachments/assets/93004853-7add-4ad0-8f24-c44607a0ac19)
## Summary—Purposes and Brief Architecture
RNN and it's variation can handle sequential data for forecasting purposes, but it's error getting bigger as the forecasting horizon got larger. More advanced architecture such transformer show good result on Long-Term Time Series Forecasting (LTSF), but it's computationally expensive. This led to a question, can RNN—that is architecturally simpler—modified for LTSF purpose? Two approaches that can be take to modify the RNN architecture are:
1. Instead of taking each point to make decision, we group some point into segment. This can reduce iteration thus solving vanishing/exploding gradient problem.
2. Making each point paralel with positional encoding to preserve sequence information.

For further detail about the architecture and methodology, I suggest to read the [paper](https://arxiv.org/pdf/2308.11200v1) or my explanation
