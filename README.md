# LSTM-Autoencoder
Anomaly detection using Pytorch 

Data used - ECG data

classes-['Normal',
         'R on T',
          'PVC',
          'SP',
          'UB']

Created an encoder and decoder consisting of LSTM layers to create an autoencoder.

Autoencoder was trained on the data labelled as normal heartbeat.

To detect anomalies a threshold is set based on loss distribution on normal heartbeat and loss values above this threshold were detected as anomalies.

Libraries Used

Pytorch
pandas
numpy
seaborn

Network architecture comprises of an encoder and decoder made using LSTM and Linear layers.

Threshold value set 26








