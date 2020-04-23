# DL_EXP_PC
Deep learning experiment - pixel classification

A simple example of the creation and application of a neural network to pixel classification using keras.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-toc.ipynb)

    
|chapter|content|open in colab|open locally|
|---|---|---|---|
| Pixel classification | example of a small fully connected network that classifies pixel in images | [DL01](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-pixel-classification.ipynb) | [DL01](./DL01-pixel-classification.ipynb) |
| 01 - installation | keywords, functions, modules and packages,  booleans, if-statement, help, shell-commands | [Cell01](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell01-explanations.ipynb) | [Cell01](./DL01-cell01-explanations.ipynb) |
| 02 - paths, patch and sample size | variables, integers, floats, strings | [Cell02](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell02-explanations.ipynb) | [Cell02](./DL01-cell02-explanations.ipynb) |
| 03 - reading the input and ground-truth image| loading and displaying tif-images | [Cell03](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell03-explanations.ipynb) | [Cell03](./DL01-cell03-explanations.ipynb) |
| 04 - getting foreground and background pixels| tupels, lists, numpy arrays and the python imaging library (PIL) | [Cell04](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell04-explanations.ipynb) | [Cell04](./DL01-cell04-explanations.ipynb) |
| 05 - random sampling of training data| pseudo random numbers, for-loops, while-loops, objects and classes, random sampling | [Cell05](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell05-explanations.ipynb) | [Cell05](./DL01-cell05-explanations.ipynb) |
| 06 - preparation of training data | creating the network input from intensities in  pixel neighborhoods | [Cell06](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell06-explanations.ipynb) | [Cell06](./DL01-cell06-explanations.ipynb) |
| 07 - shuffle and deal | shuffling feature vectors and labels | [Cell07](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell07-explanations.ipynb) | [Cell07](./DL01-cell07-explanations.ipynb) |
| 08 - **creating the network** | keras, sequantial model, adding layers, compiling, activation, metrics, loss, optimizer, visualization  | [Cell08](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell08-explanations.ipynb) | [Cell08](./DL01-cell08-explanations.ipynb) |
| 09 - **training the network** | fitting the model, history of loss and accuracy, validation split, epochs, batch size, testing | [Cell09](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell09-explanations.ipynb) | [Cell09](./DL01-cell09-explanations.ipynb) |
| 10 - visualizing performance | creating plots with matplotlib and interactive plots with mpld3  | [Cell10](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell10-explanations.ipynb) | [Cell10](./DL01-cell10-explanations.ipynb) |
| 11 - classifing a single feature vector | predict, predict_classes, flatten  | [Cell11](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell11-explanations.ipynb) | [Cell11](./DL01-cell11-explanations.ipynb) |
| 12 - extracting feature vectors from images | manually setting weights, saving and loding a model, neighborhoods to features  | [Cell12](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell12-explanations.ipynb) | [Cell12](./DL01-cell12-explanations.ipynb) |
| 13 - creating the output folder and getting the input paths | isdir, listdir, join paths, list comprehension, sorting | [Cell13](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell13-explanations.ipynb) | [Cell13](./DL01-cell13-explanations.ipynb) |
| 14 - **classifying pixels in images** | image segmentation, thresholding, cropping, writing tiff images | [Cell14](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell14-explanations.ipynb) | [Cell14](./DL01-cell14-explanations.ipynb) |
| 15 - visualizing results | matplotlib, pyplot, subplots and imshow | [Cell15](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-cell15-explanations.ipynb) | [Cell15](./DL01-cell15-explanations.ipynb) |
| A one unit network | an example with the smallest network possible containing only one unit | [Bonus track](https://colab.research.google.com/github/MontpellierRessourcesImagerie/DL_EXP_PC/blob/master/DL01-one-unit-network.ipynb) | [Bonus track](./DL01-one-unit-network.ipynb) |
