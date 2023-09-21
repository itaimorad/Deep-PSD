# Deep-PSD: A Model-Based Deep Learning Algorithm for Detection and Classification at High Event Rates

This repository includes the source code used in our recent paper:

Itai Morad, Max Ghelman, Dimitry Ginzburg, Alon Osovizky, and Nir Shlezinger, "Model-Based Deep Learning Algorithm for Detection and Classification at High Event Rates"

# Abstract

Pulse shape discrimination (PSD) is required for many radioactive particle monitoring applications. Conventional PSD methods commonly struggle at high event rates in the presence of pileup, and are therefore utilized for low event rates. In this work we  developed a PSD algorithm, that combines classic approaches with deep learning techniques. The algorithm provides both detection and classification of the pulses in high event rates. Common PSD algorithms for high event rates are often limited to two piled-up pulses, without addressing the detection of the piled-up pulses. Our algorithm is designed and tested for detection and classification under severe pileup conditions, where three or more pulses are piled-up. We have tested the algorithm on both experimental data from a CLYC detector and on synthetic data. The algorithm's detection and discrimination performance is compared to state-of-the-art methods of PSD and detection. The algorithm's performance is characterized under varying event rates, SNR conditions, and neutron to gamma event rate ratios.

# Overview

This repository consists of following Python scripts:

- Create_Simulated_Neutrons_and_Gammas.ipynb handles the creation of synthetic pulses based on user specified paramters. This notebook is used to create data for training, validation, and testing, along with the neutron and gamma ray templates used later on.
- General_Functions.ipynb defines functions used in this repository.

Deep Detector Module:
- Deep_Detector_Functions.ipynb defines functions for the deep detector.
- Deep_Detector_Networks.ipynb defines the Deep Detector model.
- Deep_Detector_No_Margin_Networks.ipynb defines the model of the Deep Detector without the use of margins.
- Training_Detection_Algorithms.ipynb is dedicated to training the detection algorithms.
- Testing_Detection_Algorithms.ipynb is dedicated to testing the detection algorithms.

Deep Classifier Module:
- Classification_Algorithm_Functions.ipynb defines functions for the classification algorithms and the DNN-based algorithms models.
- Training_Classification_Algorithms.ipynb is dedicated to training the classification algorithms.
- Testing_Classification_Algorithms.ipynb is dedicated to testing the classification algorithms.

Deep PSD Method:
- Training_the_Deep_PSD_Method.ipynb is dedicated to training the Deep PSD Method.
- Testing_the_Deep_PSD_Method.ipynb is dedicated to testing the Deep PSD Method.
