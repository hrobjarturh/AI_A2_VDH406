# AI_A2_VDH406
Recurrent Neural Networks

# Simple Recurrent Networks
## Notebook: AI_RNN1_only rnn.ipynb
### Libraries needed for compiling:
To run this notebook, the user is expected to have NumPy, PyTorch and matplotlib installed on their machine.
### Configurations:
At the top of the notebook it is possible to change the shape and strength of the signals. 
The parameters starts as:
```
signal_length = 100
signal_repeats = 3
predict_ahead = 1
noise_strength = 0.00
total_series_length = signal_length * signal_repeats
```
### Running:
If all libraries are installed and configurations are set, the user can run the notebook in its entirety from start to finish.

# Long-Short Term Memory Networks
## Notebook: AI_RNN1_vdh406
### Libraries needed for compiling:
To run this notebook, the user is expected to have NumPy, PyTorch and matplotlib installed on their machine.
### Configurations:
At the top of the notebook it is possible to change the shape and strength of the signals. 
The parameters starts as:
```
signal_length = 100
signal_repeats = 3
predict_ahead = 1
noise_strength = 0.00
total_series_length = signal_length * signal_repeats
```
### Running:
If all libraries are installed and configurations are set, the user can run the notebook in its entirety from start to finish.

#  Recurrent Neural Networks in PyTorch
## Notebook: AI_RNN2_minimal_vdh406.ipynb
### Libraries needed for compiling:
To run this notebook, the user is expected to have NumPy, PyTorch and Pandas installed on their machine.
(torch.summary is also required but can be downloaded from the notebook.)

### Configurations:
This notebook can run different types of RNN's. The user must choose (near the top of the notebook) one of the following: 

*   Original model = "LSTM"
*   Bidirectional model = "LSTM_bi"
*   2 layer model = "LSTM_2layer"
*   1-d convolution model = "LSTM_conv"
*   All-in-one = "LSTM_all"

You can also choose if you want gradient clipping or not. You can also set the threshold, which is currently set at 0.5.

### Running:
Before running the notebook there are some cells you might have to alter or skip:
* Mounting Google Drive is not necessary (if you want to save the models through drive and you are using Google Colab).
* Save the model, you have to change the desired path. It is only not necessary but might save time.
* Load the model, you also have to change the path to the same path as you saved it.

Now that you have configured the notebook you can run it in its entirery.

