# Abstract
In this report, I aim to find a modern probabilistic deep learning model with the capability of capturing long-term dependencies in sequencial modeling. The main candidate here is the transformer model. \
\
There are many statistical models about time series, for example ARIMA, GARCH, state space model, exponential smoothing and structural time series models. In this new era of deep learning, many new models come out like LSTM, RNN, TCN, WaveNet and so on. There are also some combined methods like DeepAR (LSTM + AR) and DeepState (RNN + state space model). These models has their probablistic variants like the probabilistic LSTM or probabilistic RNN.\
\
Recently transformer model has been shown to have the capability of capturing a long-term dependency, like the ConvTrans, TFT, Informer, Autoformer and so on. It is also proposed by (Tang et al. 2021) that transformer structures can be combined with the variational state space models to create a deep probabilistic model for the time series.\
\
My goal is to find a powerful probabilitic deep learning model that can perform well in long sequencies, especially focusing on the transformer model since it has not been explored a lot yet, and I believe that transformer's success in CV and NLP can be reproduced in time series analysis.
