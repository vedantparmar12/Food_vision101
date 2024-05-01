# Food 101 Model Improvements

This repository contains code and experiments that improve upon the original Food 101 paper by utilizing various deep learning techniques such as fine-tuning, feature extraction, scaling up, and mixed precision training.

## Introduction

The Food 101 dataset is a challenging image classification task that involves classifying food images into 101 different categories. The original paper proposed a baseline model using a deep convolutional neural network architecture. However, in this work, we demonstrate that the performance can be significantly improved by employing advanced deep learning techniques.

## Techniques Used

1. **Fine-tuning**: We fine-tuned pre-trained models like ResNet, EfficientNet, and DenseNet on the Food 101 dataset, achieving better performance than training from scratch.

2. **Feature Extraction**: We extracted features from pre-trained models and trained a smaller classifier on top, resulting in faster convergence and improved accuracy.

3. **Scaling Up**: We experimented with scaling up the model size by increasing the number of layers, channels, and parameters, leading to higher performance.

4. **Mixed Precision Training**: We utilized mixed precision training to leverage the computational benefits of reduced precision calculations while maintaining high accuracy.

## Results

Our best model achieves a top-1 accuracy of **91.1%** on the Food 101 test set, surpassing the original paper's performance by a significant margin. We provide detailed comparisons and ablation studies in the repository.

## Getting Started

To replicate our results or build upon our work, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/food101-improvements.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Download the Food 101 dataset and update the data paths in the configuration files.
4. Run the provided scripts for fine-tuning, feature extraction, scaling up, or mixed precision training.

Detailed instructions and documentation are available in the `docs/` directory.

## Contributing

We welcome contributions to this project! If you have any improvements, bug fixes, or new ideas, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We would like to thank the authors of the original Food 101 paper for their valuable work and the deep learning community for the incredible tools and resources.
