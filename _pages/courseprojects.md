---
layout: archive
title: "Course Projects"
permalink: /courseprojects/
author_profile: true
---

* Sep- Nov 2024: Image Enhancement and Compression Coding Techniques Based on MATLAB
  * Utilized MATLAB to implement and optimize traditional digital image processing techniques, focusing
on image enhancement and compression to improve processing efficiency and effectiveness.
  * Developed and applied spatial domain filtering techniques, including neighborhood averaging and
median filtering for noise reduction, boundary-preserving filtering and gradient operations for edge
enhancement, and Laplacian operations for improving image contrast and sharpness.
  * Implemented frequency domain filtering techniques, such as ideal low-pass, Butterworth low-pass, ideal
high-pass, and Butterworth high-pass filters, to remove noise and enhance image details. Applied
high-boost filtering, band-pass/band-stop filtering, and homomorphic filtering to handle specific
frequency components and improve illumination variations.
  * Explored morphological image enhancement techniques and analyzed and implemented image
compression methods.

* Nov-Dec 2024: Tang Poetry Text Generation Based on Char-RNN Using PyTorch
  * Preprocessed the dataset of Tang poems by converting each poem into character sequences;
Encapsulated the dataset into a PoemDataset class and used DataLoader for efficient batch processing
during training.
  * Designed the model architecture, including an embedding layer, an RNN layer and a fully connected layer. Implemented a get_next_token method for step-by-step prediction of the next character during text
generation.
  * Trained the model by minimizing the cross-entropy loss function. Used the Adam optimizer with a
learning rate of 0.0005 and monitored training progress by printing loss values every 500 steps over
100 epochs.

* Nov-Dec 2024: AssociationRuleMiningforSelf-ServiceConvenienceStoreSalesBasedonAprioriAlgorithm
  * Processed a dataset containing 10,000 purchase records from 2,240 customers and 166 different
products, using Pandas for data cleaning, preprocessing, and transformation into a transactional dataset.
  * Implemented the Apriori algorithm to generate candidate itemsets, calculate support, and filter frequent
itemsets, deriving association rules with confidence and lift metrics to identify valuable patterns.
  * Identified key purchasing patterns, including the highest support combination ("other vegetables" and
"whole milk" with 7.23% support) and the highest confidence combination ("curd" and "whole milk" with 48.59% confidence).

* Jun-Jul 2024: Design of Double Closed-loop Speed Control System for DC Motor
  * Modeled the current loop and speed loop of the motor using MATLAB's Simulink tool.
  * Simplified the regulator structure by performing appropriate transformations and approximations on
the inherent characteristics of the known system; Determined the relevant P, I, and D parameters of the
regulator according to the required performance indicators.
  * Simulated various operating states of the motor for speed loop simulation and inspected the simulation
effect based on the simulation waveforms.
