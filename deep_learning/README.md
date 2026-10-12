# Deep Learning Curriculum

This track is the Deep Learning continuation after the Machine Learning modules. It should be built slowly and carefully, one notebook at a time.

Every notebook should follow the same teaching pattern:

```text
definition → where used → why used → intuition → formula → visual → dataset example → code → output meaning → common mistakes
```

## Module Index

| Module | Notebook | Status |
|---|---|---|
| 01 | [Deep Learning Foundations](modules/Module_01_Deep_Learning_Foundations.ipynb) | Created |
| 02 | Math for Deep Learning | Planned |
| 03 | Neurons, Perceptrons, and Multilayer Perceptrons | Planned |
| 04 | Forward Pass, Activations, Loss Functions, and Output Layers | Planned |
| 05 | Backpropagation, Computational Graphs, and Automatic Differentiation | Planned |
| 06 | Gradient Descent, Optimizers, and Learning Rate Strategy | Planned |
| 07 | Practical Training Methodology for Deep Networks | Planned |
| 08 | Initialization, Regularization, Normalization, and Stabilization | Planned |
| 09 | Computer Vision with Convolutional Neural Networks | Planned |
| 10 | Modern CNN Architectures and Transfer Learning | Planned |
| 11 | Sequence Modeling with RNN, LSTM, and GRU | Planned |
| 12 | Attention and Transformer Foundations | Planned |
| 13 | Embeddings, Autoencoders, and Representation Learning | Planned |
| 14 | Generative Deep Learning Models | Planned |
| 15 | Graph Neural Networks | Planned |
| 16 | Deep Reinforcement Learning | Planned |
| 17 | Deep Learning Evaluation, Debugging, and Interpretability | Planned |
| 18 | Deployment, Compression, Acceleration, and MLOps for Deep Learning | Planned |

## Complete Deep Learning Module Plan

### Module 01: Deep Learning Foundations

- What deep learning is and how it fits after machine learning.
- Traditional ML feature engineering vs deep representation learning.
- Parameters, weights, bias, layers, neurons, activations, logits, probabilities.
- Data representation: tabular tensors, image tensors, sequence tensors, graph tensors.
- Common tasks: classification, regression, object detection, segmentation, forecasting, recommendation, anomaly detection, generation, control.
- Why deep learning became powerful: data, GPUs, better activations, better initialization, better optimizers, better architectures.
- First visual examples: tensor shapes, neuron computation, non-linear decision boundaries.
- Dataset examples: synthetic two-moons classification and scikit-learn digits images.

### Module 02: Math for Deep Learning

- Scalars, vectors, matrices, tensors, axes, rank, shape, dtype.
- Matrix multiplication, dot product, transpose, identity matrix, inverse intuition, broadcasting.
- Norms, distances, cosine similarity, projections.
- Functions, derivatives, partial derivatives, chain rule, gradients.
- Jacobian and Hessian intuition.
- Probability, likelihood, log-likelihood, entropy, cross-entropy, KL divergence.
- Numerical stability: overflow, underflow, log-sum-exp.
- Dataset/example: small arrays, image tensors, manual probability tables.

### Module 03: Neurons, Perceptrons, and Multilayer Perceptrons

- Artificial neuron, weighted sum, bias, activation.
- Perceptron learning rule, linear separability, decision boundary.
- XOR limitation of single-layer perceptrons.
- Hidden layers, MLP, depth vs width, universal approximation intuition.
- Binary, multiclass, and regression networks.
- Dataset/example: AND/OR/XOR truth tables and synthetic 2D classification.

### Module 04: Forward Pass, Activations, Loss Functions, and Output Layers

- Forward propagation through layers.
- Linear layer, affine transformation, logits.
- Sigmoid, tanh, ReLU, Leaky ReLU, ELU, SELU, GELU, Swish.
- Softmax and temperature.
- MSE, MAE, Huber loss, binary cross-entropy, categorical cross-entropy, negative log-likelihood.
- Output layer selection for regression, binary classification, multiclass classification, multilabel classification.
- Dataset/example: digits classification and small regression.

### Module 05: Backpropagation, Computational Graphs, and Automatic Differentiation

- Computational graph, local derivatives, upstream/downstream gradients.
- Chain rule through addition, multiplication, matrix multiplication, activations, and loss.
- Manual backprop for one neuron and one tiny MLP.
- Vanishing gradients, exploding gradients, dead ReLUs.
- Automatic differentiation, dynamic graph vs static graph idea.
- Gradient checking.
- Dataset/example: hand-calculated tiny network.

### Module 06: Gradient Descent, Optimizers, and Learning Rate Strategy

- Loss surface, gradients, step direction.
- Batch gradient descent, stochastic gradient descent, mini-batch gradient descent.
- Momentum, Nesterov momentum, AdaGrad, RMSProp, Adam, AdamW.
- Learning rate, decay, cosine schedule, warmup, cyclic learning rates.
- Gradient clipping and exploding-gradient control.
- Batch size effects, noisy gradients, saddle points, plateaus.
- Dataset/example: 2D loss surface and small neural network training curves.

### Module 07: Practical Training Methodology for Deep Networks

- Train/validation/test split, data loaders, batching, epochs, iterations.
- Training loop and validation loop.
- Metrics for classification, regression, multilabel, ranking, and sequence tasks.
- Overfitting, underfitting, bias/variance in deep learning.
- Early stopping, checkpoints, experiment tracking.
- Data leakage, reproducibility, random seeds.
- Dataset/example: digits/Fashion-MNIST style classifier with learning curves.

### Module 08: Initialization, Regularization, Normalization, and Stabilization

- Why initialization matters.
- Xavier/Glorot initialization, He initialization, orthogonal initialization.
- L1/L2 regularization, weight decay vs L2, dropout, label smoothing.
- Data augmentation, mixup, CutMix.
- Batch normalization, layer normalization, group normalization, instance normalization.
- Residual connections, skip connections, gradient flow.
- Dataset/example: same model trained with/without regularization and normalization.

### Module 09: Computer Vision with Convolutional Neural Networks

- Image tensors, channels, pixel normalization.
- Convolution kernel/filter, stride, padding, dilation.
- Feature maps, receptive field, parameter sharing, translation equivariance.
- Pooling: max, average, global average.
- Flattening vs global pooling.
- CNN classifier pipeline.
- Dataset/example: digits/MNIST image classification, filter visualization, feature maps.

### Module 10: Modern CNN Architectures and Transfer Learning

- LeNet, AlexNet, VGG, Inception/GoogLeNet, ResNet, DenseNet, EfficientNet, MobileNet.
- Depthwise separable convolution.
- Residual blocks and bottleneck blocks.
- Transfer learning, freezing layers, feature extraction, fine-tuning.
- Image augmentation for transfer learning.
- Dataset/example: small image classifier using pretrained-style feature extraction or local small image data.

### Module 11: Sequence Modeling with RNN, LSTM, and GRU

- Sequence data and temporal dependency.
- One-to-one, one-to-many, many-to-one, many-to-many tasks.
- RNN hidden state, recurrence, backpropagation through time.
- Vanishing gradient in long sequences.
- LSTM gates: forget, input, candidate, output.
- GRU update/reset gates.
- Bidirectional RNNs, stacked RNNs, teacher forcing.
- Dataset/example: text classification or time-series forecasting.

### Module 12: Attention and Transformer Foundations

- Why attention was introduced.
- Query, key, value.
- Scaled dot-product attention.
- Self-attention, cross-attention, causal attention.
- Multi-head attention.
- Positional encoding.
- Transformer encoder block and decoder block.
- Residual connection, layer norm, feed-forward network.
- Dataset/example: toy sentence attention matrix and small sequence classification.

### Module 13: Embeddings, Autoencoders, and Representation Learning

- Embeddings for categories, text, images, and users/items.
- Encoder, decoder, bottleneck, latent vector.
- Undercomplete autoencoder, sparse autoencoder, denoising autoencoder, convolutional autoencoder.
- Reconstruction loss.
- Latent-space visualization.
- Autoencoder anomaly detection.
- Dataset/example: digits reconstruction and anomaly score.

### Module 14: Generative Deep Learning Models

- Generative modeling inside DL, separate from the later Generative AI track.
- Latent variable models.
- Variational Autoencoders: encoder, decoder, mean/log-variance, reparameterization trick, KL term.
- GANs: generator, discriminator, adversarial loss.
- DCGAN, conditional GAN, mode collapse.
- Normalizing flows intuition.
- Diffusion model intuition: noise schedule, denoising, sampling.
- Dataset/example: digits generation/reconstruction visuals.

### Module 15: Graph Neural Networks

- Graphs, nodes, edges, adjacency matrix, node features, edge features.
- Message passing.
- Graph convolution networks.
- GraphSAGE.
- Graph attention networks.
- Node classification, graph classification, link prediction.
- Oversmoothing and graph depth.
- Dataset/example: small synthetic graph with node classification.

### Module 16: Deep Reinforcement Learning

- RL recap: agent, environment, state, action, reward, episode.
- Value function, Q-function, policy.
- Deep Q-Network, target network, replay buffer.
- Exploration vs exploitation, epsilon-greedy.
- Policy gradients, actor-critic, advantage.
- PPO intuition.
- Dataset/example: CartPole-style environment if available, otherwise a small gridworld.

### Module 17: Deep Learning Evaluation, Debugging, and Interpretability

- Metrics for deep learning tasks.
- Learning-curve diagnosis.
- Confusion matrix, ROC-AUC, PR-AUC, calibration.
- Activation visualization, filter visualization.
- Saliency maps, integrated gradients intuition, Grad-CAM.
- Error analysis and slice-based evaluation.
- Debugging checklist: data, labels, loss, gradients, leakage, augmentation, distribution shift.
- Dataset/example: image classifier error analysis.

### Module 18: Deployment, Compression, Acceleration, and MLOps for Deep Learning

- Saving/loading models.
- Inference pipeline and preprocessing consistency.
- Batch inference vs online inference.
- CPU vs GPU inference.
- ONNX concept, TorchScript concept, TensorFlow SavedModel concept.
- Quantization, pruning, distillation.
- Latency, throughput, memory footprint.
- Monitoring, drift, rollback, model versioning.
- Dataset/example: saved classifier loaded for inference.

