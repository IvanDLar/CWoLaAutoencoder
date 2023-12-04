# CWoLaAutoencoder

Integration of the CWoLa machine learning technique with autoencoders.

A wide variety of autoencoder architectures were explored and tested during the development of this project. No code will be deleted from this repo as it is a work STILL IN PROGRESS.

To mimic some of the results found in the "Anomaly Detection in High Energy Physics using CWoLa and Autoencoders" paper, please follow the next steps.

1.- Contact me to give you the LHC2020 R&D Data set, 2 data sets for the development of this project, one containing anomalous events, and the other containing background events ant its features.

2.- Execute all the cells between the "Import Libraries and setup CPU execution" and "Data preparationCWoLa T_21"

3.- The Deep Autoencoder with MSE loss function that was used as the final proposed autoencoder in the paper is the one found in the "Plotting the roc curve using MSE | WITH callback" section.

4.- To plot the ROC Curves firs you must execute the section called "False Positive Rates Deep CWoLa and CWoLa + Autoencoder MSE".

5.- I recommend executing the "Autoencoder", "Fully Supervised" and the first CWoLa T_21 sections to aid in the performance comparison of the proposed model.

6.- Finally execute the "Plot CWoLa vs CWoLa + Deep AE vs AE vs Fullysupervised" section, then the graph will be plotted.