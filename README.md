The repository is supplementary information from the article titled "Application of a modified set of GoogLeNet and ResNet-18 convolutional neural networks towards the identification of environmentally derived-MPLs in the Yadkin-pee dee river basin". It contains visual/pictorial data as well as MATLAB code/neural networks used in the project. 

NOTE: Unknown labeling conventions are covered in the SI.

# Additional Files
Links to two file folders are below for pictorial data that was too large for the Github repository:
https://drive.google.com/drive/folders/1rozv9ilPcbPrAHJwTxZkCNn8PhKxiG2t?usp=sharing [Pictorial Spectra]
https://drive.google.com/file/d/1wZB0vCS4a29Z7bnub5uOfEAREgc0FezV/view?usp=sharing [Visual MPL Images]

# Accuracy-Loss During NN Training
This file contains the training history of the GoogLeNet and Resnet-18 neural networks trained with the version 1 and version 2 dataset. The accuracy and loss changes are tracked as well as the time of completion to 10 epochs. 

# Confusion Matrices
These are the confusion matrices showing misclassification with respect to class for the 10% holdout and not the Primpke/DongMiller holdout.

# FEDS Corroboration
This folder contains the code to perform the searching analysis (Retrofitted-AdditiveAanlysis) for the polymers in the sample as well as the FEDS transform which accentuates hidden peaks within the spectra. In addition, Miller's biological data was excised from their dataset to detect biological material as an additional control in the experiment. The "UnknownLabels" file is the top ten ranks for the microplastics collected in the study. We processed the data after we realized elemental carbon would, expectedly, result in a large similarity score (low number of peaks/carbon-containing polymers).

# MATLAB Scripts
The scripts contain the .m and .pdf versions of the code that train the neural networks based on pictorial spectral data. The other scripts can generate new pictorial graphical data, output existing data, and label softmax output.

# Pictorial Data
Data is organized by polymer type and spectrscopy mode. What isn't apparent is the differentiation between 300 and 500 files per class. 300, for V1, refers to 100 from pristine, 100 from microplastics (colorants/additives), and 100 from degraded microplastics. 500 refers to the addition of more diverse environmentally-degraded microplastics from sources explained in the methodology of the report.

# Regression (River Basin)
Here, data from the number concentration calculation is used to estimate microplastic abundance across the Yadkin river basin. Various code generates relationships with which we determined the most optimal via error from experimental data.

"InterpolationCNN_OS.m" should guide you on where particular variables come into play.

# Spectral Data of Unknown MPs (Final 149)
The "OriginalSet" shows the unprocessed data from the Witec Raman which is in the european comma-delimited convention. Scripts for processing this convention and organizing the data are available here as well as the transformed set. Processing the range and resolution of the data (OpenSpecy) was done "UnknownMPMASTER.csv". No baseline correction or noise reduction was performed.

Anything else unexplained should be self-explanatory. If you are still lost, please email me: wawilliams1@aggies.ncat.edu OR wesawill@stanford.edu.



