# InternationalBarcodeOfLife
Collaborating on research for the International Barcode of Life BIOSCAN program


Conducting research to enable a far more extensive and detailed understanding of global biodiversity and the interactions between species and ecosystems.
Collaboration on the BIOSCAN Program, part of the International Barcode of Life (iBOL) project.
Increased Machine Learning model accuracy using Confident Learning for error detection in data


Working on 2 approaches:

Removing bad data from the training set:

Increased Machine Learning model accuracy using Confident Learning for error detection in data.
Used CleanLab for this, testing on MNIST dataset. Detected 155 labels that are high risk as mislabeled.
Implemented on actual dataset and waiting to measure results.

Having the CNN identify and group similar taxas in the second last layer of neural network.
Testing on MNIST dataset, using TSNE and UMAP to form groupings in data .

Files:

MNIST_Bad_Label_Detection_CleanLab.ipynb
- Used to find mislabeled data
  
MNIST_Bad_Data_Pruning.ipynb
- Used to remove the mislabeled data
  
MNIST_Data_Augmentation.ipynb
- Augments existing dataset to create more data to train on
