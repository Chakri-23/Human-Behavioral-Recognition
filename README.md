# Human-Behavioral-Recognition
We have come up with a way to classify human behavioral patterns into various categories/labels using a Deep Learning Approach.

## FLOW OF EXECUTION

![flowchart](https://github.com/Chakri-23/Human-Behavioral-Recognition/assets/101948154/3d7f0e51-651d-4060-9704-bec7a219e584)


### APPROCHES USED:
## 1. ConvLSTM
ConvLSTM (Convolutional Long-Short Term Memory) is a type of recurrent neural network for spatio-temporal prediction that uses convolutional structures in both the input-to-state and state-to-state transitions. It determines the future state of a certain cell in the grid by the inputs and past states of its local neighbors.0 ConvLSTM uses convolutions in the LSTM layers for the hidden and cell states, as opposed to classic matrix multiplication with the CNN-LSTM. It is a better choice if the design is based on sequence-to-sequence

## 2. LRCN
LRCN stands for "Long-Short Term Memory Recurrent Convolutional Network." It is a type of neural network architecture that combines Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks. LRCN is specifically designed for tasks involving sequential data, such as video analysis, action recognition, and video captioning.

We have trained the model on multiple datasets. Some of them are:
1. UCF50
2. Violent_Flows
3. UCF_Crime
4. Real-Life-Violence-Dataset

We make predictions based on the model which acquires the better accuracy in the evaluation process. The outlines of the models used are as follows: 

![ConvLSTM-model](https://github.com/Chakri-23/Human-Behavioral-Recognition/assets/101948154/7f9d1775-66b4-469d-abf2-11f015f42f24)

![LRCN-model](https://github.com/Chakri-23/Human-Behavioral-Recognition/assets/101948154/5f4a5806-f481-42f7-8a06-35978be95542)

The following are the **Loss vs Validation Loss** and **Accuracy vs Validation Accuracy** plots of both the models:

ConvLSTM

![ConvLSTM-AccVsValAcc](https://github.com/Chakri-23/Human-Behavioral-Recognition/assets/101948154/08218777-f43c-4f5b-95d7-d483aa795f39)

![ConvLSTM-LossVsValLoss](https://github.com/Chakri-23/Human-Behavioral-Recognition/assets/101948154/e2b08d08-7530-4da1-8ce6-03673259e13b)

LRCN

![LRCN-Accuracy](https://github.com/Chakri-23/Human-Behavioral-Recognition/assets/101948154/18d34728-61a3-4d00-a847-d9adce868983)

![LRCN-Loss](https://github.com/Chakri-23/Human-Behavioral-Recognition/assets/101948154/a40a865e-1893-43fb-b2a0-fc43962a7d0d)

We have provided the saved models and python notebooks of the project above. In order to run 
1. Download all the necessary libraries
2. Run the cells in sequential order
3. Follow the steps from the notebook
4. You have to upload the path of the video file you would like to process manually for now, we are working on developing a fully fledged front-end for the project and will provide you with a UI as soon as possible (As this is still a project under development).
