# Deep-PSD: A Model-Based Deep Learning Algorithm for Detection and Classification at High Event Rates

This repository includes the source code used in our recent paper:

Itai Morad, Max Ghelman, Dimitry Ginzburg, Alon Osovizky, and Nir Shlezinger, "Model-Based Deep Learning Algorithm for Detection and Classification at High Event Rates"

# Abstract

Pulse shape discrimination (PSD) is required for many radioactive particle monitoring applications. Conventional PSD methods commonly struggle at high event rates in the presence of pileup, and are therefore utilized for low event rates. In this work we  developed a PSD algorithm, that combines classic approaches with deep learning techniques. The algorithm provides both detection and classification of the pulses in high event rates. Common PSD algorithms for high event rates are often limited to two piled-up pulses, without addressing the detection of the piled-up pulses. Our algorithm is designed and tested for detection and classification under severe pileup conditions, where three or more pulses are piled-up. We have tested the algorithm on both experimental data from a CLYC detector and on synthetic data. The algorithm's detection and discrimination performance is compared to state-of-the-art methods of PSD and detection. The algorithm's performance is characterized under varying event rates, SNR conditions, and neutron to gamma event rate ratios.

# Overview

This repository consists of following Python scripts:

-  XXX handles the creation of synthetic pulses based on user specified paramters.
-  XXX defines and creates signals and observations used for training the detection methods.
-  
-  XXX defines the classical and model-based detection methods used for simulation.
-  XXX defines the classical and model-based PSD methods used for simulation.
