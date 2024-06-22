# Music Generator using Deep Learning
## Description
This project utilizes deep learning techniques to generate music. By training a neural network on a dataset of musical pieces, the model learns to create new, original compositions.

## Model Used:
1. Recurrent Neural Networks (RNN)
- Recurrent Neural Networks (RNNs) are a type of artificial neural network designed for sequential data.
- Unlike traditional feedforward neural networks, RNNs have connections that form directed cycles.
- This enables them to maintain a hidden state that can capture information from previous time steps, making them ideal for tasks such as language modeling and time series prediction.

2. Long Short-Term Memory (LSTM)
- Long Short-Term Memory (LSTM) is a special kind of RNN capable of learning long-term dependencies.
- Introduced by Hochreiter and Schmidhuber (1997), LSTMs address the vanishing gradient problem by using a more complex architecture.
- They consist of cells with three types of gates: input, forget, and output gates, which regulate the flow of information and allow the network to maintain a longer memory of previous states.

3. WaveNet
- WaveNet is a deep generative model introduced by DeepMind for generating raw audio waveforms.
- Unlike traditional RNNs or LSTMs, WaveNet uses dilated causal convolutions, allowing the model to efficiently handle long-range dependencies in the input data.
- This architecture makes WaveNet particularly suitable for audio and speech synthesis, achieving state-of-the-art results in natural-sounding audio generation.

Usage:

Clone the Repository:

```git clone https://github.com/your-username/music-generator.git ```


```cd music-generator```

Start Jupyter Notebook:

```jupyter notebook```

Open musicGenerator.ipynb and run the cells to train the model and generate music.
