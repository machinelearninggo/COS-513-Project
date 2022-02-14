# Abstract
In this report, I aim to find a modern probabilistic deep learning model with the capability of capturing long-term dependencies in sequencial modeling. The main candidate here is the transformer model. \
\
There are many statistical models about time series, for example ARIMA, GARCH, state space model, exponential smoothing and structural time series models. In this new era of deep learning, many new models come out like LSTM, RNN, temporal convolutional networks (TCN) [1], WaveNet [2] and so on. There are also some combined methods like DeepAR (LSTM + AR) [3] and DeepState (RNN + state space model) [4]. These models has their probablistic variants like the probabilistic LSTM or probabilistic RNN.\
\
Recently transformer model has been shown to have the capability of capturing a long-term dependency, like the ConvTrans [5], TFT [6], Informer [7], Autoformer [8] and so on. It is also proposed by [9] that transformer structures can be combined with the variational state space models to create a deep probabilistic model for the time series.\
\
My goal is to find a powerful probabilitic deep learning model that can perform well in long sequencies, especially focusing on the transformer model since it has not been explored a lot yet, and I believe that transformer's success in CV and NLP can be reproduced in time series analysis. Meanwhile, the other models like VAE and fully visible belief networks (FVBN) are worth to try. The target can be improving the prediction accuracy or learning representation of time series data, depending on the progress and findings during the project.





\
\
\
Reference:

[1] arXiv:1608.08242\
[2] arXiv:1609.03499\
[3] arXiv:1704.04110\
[4] https://papers.nips.cc/paper/2018/file/5cf68969fb67aa6082363a6d4e6468e2-Paper.pdf\
[5] arXiv:1907.00235\
[6] arXiv:1912.09363v3\
[7] arXiv:2012.07436\
[8] arXiv:2106.13008\
[9] https://proceedings.neurips.cc/paper/2021/file/c68bd9055776bf38d8fc43c0ed283678-Paper.pdf
