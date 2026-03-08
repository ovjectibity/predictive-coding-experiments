Experiments with predictive coding networks for text generation. 

Roadmap: 
1. Replicate CFAIR training described in the first reference paper
2.  Transformers for next token generation.
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