<h1 align="center">MNIST-SemiSupervised-PseudoLabels</h1>

<p align="justify">
A focused exploration into enhancing the accuracy of MNIST digit predictions through semi-supervised learning with a minimal set of 100 labeled samples. This project employs pseudo-labels to effectively use both labeled and unlabeled data, utilizing TensorFlow to build and implement models. It serves as a concise demonstration of improving prediction accuracy with limited labeled data.
</p>

<h2>Methodology</h2>

<p align="justify">
The methodology adopts a two-phase approach, emphasizing the practical application of semi-supervised learning algorithms enhanced by pseudo-labels:
</p>

<ul>
  <li><strong>Baseline Model Development:</strong> Constructs a foundational model using neural network techniques to address the MNIST dataset.</li>
  <li><strong>Semi-Supervised Learning with Pseudo-Labels:</strong> Augments model performance through the generation and use of pseudo-labels, capitalizing on the unlabeled data within the dataset for more effective learning.</li>
</ul>

<h2>Key Components</h2>

<ul>
  <li><strong>MNIST Dataset:</strong> The primary dataset comprising 70,000 black-and-white images of handwritten digits, divided into training and validation sets.</li>
  <li><strong>Neural Networks (NN) and Convolutional Neural Networks (CNN):</strong> These form the basis of our models, further refined through semi-supervised learning strategies.</li>
  <li><strong>Semi-Supervised Self Training:</strong> This innovative technique utilizes pseudo-labels for training, aiming to leverage the unlabeled dataset effectively.</li>
</ul>

<h2>Implementation</h2>

<p align="justify">
Detailing the project's implementation, this section outlines the data preparation, architectural decisions for NN and CNN models, and the integration of dropout and pseudo-labels to prevent overfitting and boost model generalization. Utilizing TensorFlow and Keras, the project showcases a structured approach to model development and training.
</p>
