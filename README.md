# CS-437-Deep-Learning

Projects completed during Deep Learning course taken at Lahore University of Management Sciences.

### Neural Network Class
Implemented simple backbone neural networks classes (implemented the concept of gradient descent) using python and numpy for performing Linear regression and classification.

### Model Parameters exploration:
Implemented different optimizers (momentum, Nesterov Accelerated Gradient, RMS Prop), different weight initialization strategies (Zero initialization, Random Normal initialization, He Initialization, Xavier Initialization) and Loss functions (Mean Squared Error, Cross entropy loss, Root Mean Squared Logarithmic Error) to the neural network class implemented in another assignment in order to test performance.

### Sentiment Analysis: 
Trained 3 types of models (LSTM, Bi-LSTM, <10000 parems) to understand positive and negative tone in sentences. Each model was trained using 50000 IMDB movie reviews which were cleaned and prepared for analysis. It was split into a 70:30 train:test batches randomly. All 3 models achieved +80% accuracy as was confirmed using an independent 10 reviews at the end.

### Generative Adverserial Network(GAN): 
Used Deep Convolutional Generative Adverserial Network to generate emojis out of noise.

### Cross-View Image Retrieval: 
Created system to match satellite view images of mountains, stadiums, freeways, rivers, ships and palaces with their street view images. System was made up of three components: Feature extraction by fine tuning a VGG16 model, Similarity matching of feature vectors extracted and image retrieval based on similarity score.
