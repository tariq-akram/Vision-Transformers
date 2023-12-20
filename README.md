# Vision Transformers for CIFAR-10 Classification

This project uses Vision Transformers (ViTs) to perform image classification on the CIFAR-10 dataset using TensorFlow. The goal is to demonstrate the application of Transformer models in computer vision tasks.

## Overview

Vision Transformers have gained attention for their success in image classification tasks. In this project, we use the CIFAR-10 dataset, a widely-used dataset for image classification, to train a Vision Transformer model. The images in CIFAR-10 are resized to 32x32 pixels to fit the model architecture.

## Project Structure

- **ViT_CIFAR10.ipynb**: Jupyter Notebook file containing the code for training the Vision Transformer model.
- **.ipynb_checkpoints/**: Directory containing Jupyter Notebook checkpoints.
- **tmp/**: Temporary directory for storing intermediate files.

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/MTAhere04/Vision-Transformers.git
    cd Vision-Transformers
    ```

2. **Open and run the `ViT_CIFAR10.ipynb` notebook using Jupyter.** Make sure to have TensorFlow installed.

3. **Follow the instructions and comments in the notebook** to train the Vision Transformer model on the CIFAR-10 dataset.

## Note on Accuracy

The accuracy of the model may be limited due to a restriction on the number of training items (set to 2000) for quicker experimentation. To achieve higher accuracy, consider removing the relevant code block (Block 4) in the notebook, which allows for training on the full dataset. Be aware that training on the entire dataset may take a longer time.

## Dependencies

- TensorFlow (version 2.14)
- Other dependencies as specified in the Jupyter Notebook.

## License

This project is licensed under the [MIT License](LICENSE).
