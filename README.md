# Neural-Networks-on-EEG-Classification
TFC in the application of artificial neural networks (EEGNet) to classification of EEG (Electroencephalogram) signals in BCIs (Brain Computer Interface) - Machine Learning (Deep Learning)

Brain-computer interfaces (BCIs) are systems that allow direct communication between the human brain and external devices, using technologies such as electroencephalography (EEG) or functional magnetic resonance imaging (fMRI) to detect and record brain activity. With applications ranging from helping people with motor disabilities to games and entertainment, BCIs represent an exciting area of research, although they face challenges such as the accuracy of brain signals. 

In this context, this paper aims to use a BCI system in motor imagery to determine and classify which movement was imagined by the patient during electroencephalography (EEG) recording. The analysis used the “BCI Competition IV - Dataset 2a” database, developed by researchers from the Institute for Knowledge Discovery and the Institute for Human-Computer Interfaces, both at the Graz University of Technology in Austria, which consists of 4 different motor imagery tasks performed by 9 different individuals to test and evaluate the classifiers for data analysis. 

Several stages were carried out, ranging from the initial preparation of the data to the final analysis of the results. This included pre-processing the data, extracting and selecting relevant features, scaling these features and implementing the classifiers. In the present study, a comprehensive comparison is made between different hyperparameters for training the EEGNetV4 model, using data from the aforementioned dataset. The hyperparameters evaluated included variations in the learning rate, batch size and number of epochs. The analysis aimed to identify the combination of hyperparameters that would result in the best model performance in terms of training and testing accuracy.

- References
C. Brunner, R. Leeb, G. R. Muller-Putz, A. Schlogl, and G.Pfurtscheller, BCI Competition 2008 – Graz data set A, Institute for Knowledge Discovery, Graz University of Technology,
Austria.
Vernon J Lawhern et al 2018 J. Neural Eng. 15 056013 EEGNet: a compact convolutional neural network for EEG-based brain–computer interfaces  [Online]. Available: EEGNet: a compact convolutional neural network for EEG-based brain–computer interfaces - IOPscience

