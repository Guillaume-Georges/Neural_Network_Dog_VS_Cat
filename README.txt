Neural Network Classifier: Cats vs. Dogs

Overview
This program implements a neural network designed to differentiate between images of cats and dogs. It utilizes a two-layer architecture and is trained on a substantial dataset to learn the distinguishing features of each animal.

Dataset
The neural network is trained on a dataset comprising 23,998 images, evenly split between cats and dogs, ensuring a balanced representation of both classes. For assessing the model's performance, a separate test dataset with 1,000 images (500 cats and 500 dogs) is used.

Data Sources
Training Dataset (trainset.hdf5): 23,998 images (11,999 cats, 11,999 dogs).
Testing Dataset (testset.hdf5): 1,000 images (500 cats, 500 dogs).
The original images have been sourced from the Microsoft Cats vs Dogs Dataset on Kaggle. They have been preprocessed and converted into HDF5 format to facilitate efficient loading and handling during the training and testing phases.

Performance
While the model achieves commendable accuracy on the training set, it currently exhibits a lower accuracy on the test set. This suggests an overfitting to the training data, and further improvements are necessary for the model to generalize better to new, unseen images.