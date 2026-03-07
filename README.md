Experiments with predictive coding networks for text generation. 

Roadmap: 
1. FFNs for next token generation.
2. Training details - how to interleave inference & weight updates, accelarating training via parallel kernels, batching over samples
2a. Training over the minibatch - gradient is on the basis of avg. grad across the batch (but is avg the only way)
3. Faster inference techniques - for training stage 
4. using a separate inference network for initialisation / hybrid model
5. RNNs for generative text 
6. CNNs for OCR 

Technical notes: 
1. Inference pass is basically gradient descent over the prediction loss. 
2. The signal from the input to output is carried by the loss terms at each layer. 

References: 
1. https://arxiv.org/pdf/2506.06332
2. https://www.youtube.com/watch?v=l-OLgbdZ3kk 