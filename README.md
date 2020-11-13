# bachelor-thesis
Isfahan University of Technology - Bachelor thesis codes

## Abstract
Natural language generation is one of natural language processing sub-fields and can be considered as the opposite side of natural language understanding. In this project, the goal is to achieve a model that can generate novel poetries. To obtain this objective, different techniques in natural language processing and deep learning were used, such as Generative Adversarial Networks (GAN), Variational AutoEncoders (VAE),
and Long Short-Term Memory (LSTM), to generate Persian poetries.

For instance, a word embedding with a VAE was used to achieve a variational inference for our dataset. After that, using the obtained variational inference, new latent vectors sampled from the normal distribution and fed
in the decoder part of the network to create synthesized poets. Moreover, the model had a good result for tasks like text imputing. Finally, other models and techniques like GAN were implemented for the same task and dataset, and the results of different methods were compared to each other.