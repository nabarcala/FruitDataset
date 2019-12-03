# FruitDataset: Images of fruits for classification

## Dataset Properties

### Repository Structure
Folders [train](FruitDataset/f360/train), [test](FruitDataset/f360/test), and [val](FruitDataset/f360/val) contain images for training and testing.

The file [train.py](FruitDataset/train.py) contains the python code to train a neural network.

The file [onnx_export.py](FruitDataset/onnx_export.py) contains the python code to transform the trained model into an ONNX model.

## Image Dataset

The image dataset is based on the [Fruit 360 dataset](https://github.com/Horea94/Fruit-Images-Dataset).

## Training Scripts

The training scripts are from the [ImageNet Training in PyTorch](https://github.com/dusty-nv/pytorch-classification/tree/6b8fcd38fee76cae26e43b9bd547491813bf423d) provided by NVIDIA.
