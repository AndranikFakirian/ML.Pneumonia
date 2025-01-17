# ML.Pneumonia
Here's a project to build 3D convolutional neural networks (3D CNN) to predict the pneumonia presence.
## Abstract
This clean project code shows the steps used to build a 3D convolutional neural network (CNN) to predict the presence of viral pneumonia in computer tomography (CT) scans using self-supervised learning methods. To do this, firstly, build an autoencoder model using multiple lung datasets and augmentation methods. And secondly, build a classifier using the previously built autoencoder as a preset and the pneumonia dataset.
## Datasets
One of the datasets used in this project is by [MosMedData: Chest CT Scans with COVID-19 Related Findings](https://www.medrxiv.org/content/10.1101/2020.05.20.20100362v1) which consists of 200 3D CT scans in total for the two classes. More detail [here](https://github.com/hasibzunair/3D-image-classification-tutorial/releases/tag/v0.2).  Other datasets are downloaded using the [PlatiPy library](https://pyplati.github.io/platipy/getting_started.html) from [TCIA](https://www.cancerimagingarchive.net/).
## Usage
It's advisable to run the project on a powerful computer or in Google Colab. The code, by the way, is specially adapted to make it convenient to run from Colab.
## Acknowledgements
My mentor, [**Svetlana Danilova**](https://github.com/SvetlanaDanilova), who supervised the project, provided invaluable assistance in its creation.
## References
This project is based on a paper authored by **Hasib Zunair**. Here is his GitHub repository with this ["tutorial"](https://github.com/hasibzunair/3D-image-classification-tutorial/tree/master).
