"CNN-identification.py" is CNN network used for pre-training in "CNNfix+LSTM" method.
"cnn_ckpt" is the model produced by "CNN-identification.py".
"read-CNNckpt.py" generates the characteristics which is the input for LSTM by reading the pre-trained CNN model.("CNNfix+LSTM" method)
"CNN+LSTM.py" reads the input generated by "read-CNNckpt.py" for training.("CNNfix+LSTM" method)
"unfix-cnn-lstm（hor）.py" and "unfix-cnn-lstm（ver）.py" is the network for "CNN+LSTM" method.
