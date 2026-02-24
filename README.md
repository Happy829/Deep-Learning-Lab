# 📂 Assignments Overview

## 🔬 Experiment 1: Tensor Operations using NumPy and PyTorch

* Created 1D, 2D, and 3D tensors using NumPy and PyTorch.
* Performed basic tensor operations:
  - Element-wise addition, subtraction, multiplication, and division.
  - Dot product and matrix multiplication.
* Demonstrated indexing and slicing techniques:
  - Boolean masking
  - Extracting subtensors
  - Row/column selection and conditional indexing
* Used tensor reshaping methods:
  - .view(), .reshape(), .unsqueeze(), .squeeze() in PyTorch
  - .reshape() in NumPy (comparison included)

* Implemented broadcasting operations with tensors of different shapes and verified shape compatibility rules.
* Compared in-place vs out-of-place operations and analyzed memory efficiency.


## 🔬 Experiment 2: Neural Network from Scratch using NumPy (MNIST)

* Implemented a fully connected neural network from scratch without using deep learning frameworks.
* Loaded and preprocessed the MNIST handwritten digit dataset, including normalization and reshaping.
* Designed a multi-layer architecture consisting of:
  - Input layer
  - Hidden layers
  - Output layer
* Implemented core components manually:
  - Weight initialization
  - Forward propagation
  - Loss computation (cross-entropy)
  - Backpropagation algorithm
  - Gradient descent optimization
* Implemented activation functions such as ReLU, Sigmoid, and Softmax.
* Trained the model over multiple epochs and monitored convergence.
* Evaluated performance using accuracy metrics on validation and test data.


## 🔬 Experiment 3: Implementation of a simple neural network to classify both linearly separable and non-linearly separable datasets, using Numpy

* Implemented a neural network from scratch using NumPy to classify both linearly separable and non-linearly separable datasets.
* Generated synthetic datasets using make_classification and make_circles to study decision boundaries.
* Built a single-layer perceptron to learn linear decision boundaries and observed its limitations on complex data.
* Extended the model to a multi-layer neural network with hidden layers to handle non-linear patterns.
* Implemented forward propagation, backpropagation, and gradient descent manually without deep learning libraries.
* Experimented with non-linear activation functions such as Sigmoid, Tanh, and ReLU.
* Compared performance between linear and non-linear models to understand when deeper architectures are required.


## 🔬 Experiment 4 : Image classification using Convolutional Neural Networks (CNNs) to classify images. (Datasets: (Cats vs. Dogs) & (CIFAR-10)

* Implemented Convolutional Neural Networks (CNNs) for image classification tasks.
* Trained and evaluated models on Cats vs Dogs and CIFAR-10 datasets.
* Loaded and preprocessed image datasets (resizing, normalization, batching).
* Applied data augmentation techniques to improve model generalization.
* Designed CNN architectures with:
  - Convolutional layers
  - Activation functions (ReLU)
  - Pooling layers
  - Fully connected layers
  - Dropout for regularization
* Trained models using appropriate loss functions and optimizers.
* Evaluated model performance using accuracy and loss metrics.
* Tested trained models on unseen images to verify predictions.


## 🔬 Experiment 5 : Text Generation Using RNN(Sequential Model)

* Implemented a Recurrent Neural Network (RNN) using a Sequential model to generate text sequences.
* Learned how sequential models learn patterns and dependencies in textual data.
* Loaded and preprocessed text data (cleaning, tokenization, and sequence creation).
* Converted text into numerical format using character/word indexing.
* Created input–output sequences for training the RNN model.
* Built a Sequential RNN architecture with:
  - Embedding layer
  - Recurrent layers
  - Dense output layer with softmax activation
* Trained the model using appropriate loss function and optimizer.
* Monitored training performance using loss curves.
* Generated new text by predicting the next character/word iteratively.
* Experimented with different hyperparameters to improve text quality.
* Evaluated generated text to analyze learned language patterns.


## 🔬 Experiment 6 : Implement a Sequence-to-Sequence (Seq2Seq) model for English-to-Spanish translation

* Implemented a Sequence-to-Sequence (Seq2Seq) model to perform machine translation from English to Spanish.
* Learned encoder–decoder architecture and sequence learning concepts.
* Loaded and preprocessed bilingual text data (tokenization, cleaning, padding, and vocabulary creation).
* Converted sentences into numerical sequences suitable for neural network training.
* Built a Seq2Seq architecture consisting of:
  - Encoder (Embedding + RNN/LSTM layers)
  - Decoder (Embedding + RNN/LSTM layers + Dense output)
* Implemented teacher forcing during training to improve learning stability.
* Trained the model using appropriate loss function and optimizer.
* Evaluated translation performance using sample predictions and comparison with ground truth sentences.
* Generated translated sentences by iterative decoding from the trained model.
* Visualized training performance using loss curves.
* Analyzed challenges in sequence learning such as long dependencies and translation errors.


## 🔬 Experiment 7 : Sequence to Sequence Learning with Transformers

* Implemented a Transformer-based sequence-to-sequence (Seq2Seq) model for machine translation using PyTorch.
* Learned self-attention mechanisms and the encoder–decoder architecture.
* Loaded and preprocessed English–Spanish sentence pairs (tokenization, lowercasing, padding, and vocabulary creation).
* Split the dataset into training, validation, and testing sets.
* Implemented core Transformer components from scratch:
  - Embedding layers for source and target sequences
  - Sinusoidal positional encoding
  - Scaled dot-product attention
  - Multi-head self-attention with masking
* Built the Transformer Encoder with stacked attention and feed-forward layers, including residual connections and layer normalization.
* Built the Transformer Decoder with masked self-attention and encoder–decoder (cross) attention.
* Trained the model using teacher forcing, cross-entropy loss with padding mask, and Adam optimizer.
* Evaluated translation performance using BLEU score and sample translations.
* Compared results with traditional LSTM-based Seq2Seq models.
* Visualized training performance using plots (loss curves, BLEU score trends, etc.).
* Measured training time and analyzed model performance.


## 🛠️ Technologies Used

* Python
* NumPy
* PyTorch
* Matplotlib / Seaborn
* NLTK
* Jupyter Notebook / Kaggle


## 📊 Key Learning Outcomes

* Understanding deep learning concepts from mathematical foundations to advanced architectures.
* Practical implementation experience with NumPy and PyTorch.
* Hands-on exposure to CNNs, RNNs, LSTMs, and Transformers.
* Experience with model training, evaluation metrics, and visualization.
* Ability to analyze and compare different neural network architectures.


## 🚀 How to Run

* Clone the repository:
  - git clone https://github.com/Happy829/Deep-Learning-Lab.git
* Open notebooks using:
  - Jupyter Notebook
  - Google Colab
  - Kaggle
* Install required libraries:
  - pip install numpy torch matplotlib nltk
 

## 👨‍💻 Author

* Deep Learning Lab Assignments
* Academic coursework and practice implementations.
