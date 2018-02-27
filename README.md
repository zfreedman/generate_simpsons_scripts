# generate_simpsons_scripts
NLP system for generating Simpsons scripts based in Moe’s Tavern
## Description
This project uses TensorFlow's LSTM cell implementationts (Basic/Multi) to construct an RNN (recurrent neural network) to generate new TV scripts based off of scenes from The Simpsons which take place in Moe's Tavern. The script language is vectorized using Python's Counter() class, which moves a sentence like "Hi there!" into a 2-dimensional space, where the *n* dimensions are based off of the number of unique words in the input, ignoring punctuation and spacing.
