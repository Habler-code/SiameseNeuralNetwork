# Siamese Neural Network
This repository is dedicated to the implementation of a Siamese Neural Network for one-shot image recognition tasks. Utilizing the Labeled Faces in the Wild-a (LFW-a) dataset, our model is enhanced with data augmentation techniques and early stopping measures to mitigate overfitting.


## Dataset

I employed the Labeled Faces in the Wild-a (LFW-a) dataset for this project. This dataset consists of image pairs, with each pair either showcasing images of the same individual or different ones, each coming with an appropriate label. The dataset comprises 1980 training pairs and 220 test pairs, accumulating to a total of 2200 pairs.

## Model

Our model is based on the Siamese Neural Network architecture described in the paper "Siamese Neural Networks for One-shot Image Recognition" by Koch et al. Moreover, I have modify the architecture to include data augmentation and early stopping to prevent overfitting.
```
bibtex
@inproceedings{koch2015siamese,
  title={Siamese neural networks for one-shot image recognition},
  author={Koch, Gregory and Zemel, Richard and Salakhutdinov, Ruslan and others},
  booktitle={ICML deep learning workshop},
  volume={2},
  number={1},
  year={2015},
  organization={Lille}
}
```

<img width="565" alt="image" src="https://github.com/Habler-code/SiameseNeuralNetwork/assets/69906239/f617caa7-ebdb-4b6c-992d-a7e232da9445">

## Performance Results
Our Siamese Neural Network model displayed a promising performance with an accuracy of 85% on the LFW-a test set. You can view the details of our experiments via TensorBoard, as displayed in the image below:

<img width="323" alt="image" src="https://github.com/Habler-code/SiameseNeuralNetwork/assets/69906239/574c88e1-ff89-4d33-9afb-c03de7f34137">

The following table shows the results of our experiments with different parameter combinations and 
architectures.
<img width="278" alt="image" src="https://github.com/Habler-code/SiameseNeuralNetwork/assets/69906239/d26ac33b-9144-4d70-8e84-6a8beab27639">

## Requirements
- TensorFlow
- NumPy
- Matplotlib

