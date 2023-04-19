This repository contains the data from the research paper "Residual stress prediction of arc welded austenitic pipes with artificial neural
network ensemble using experimental data", D.K.Rissaki et al., 2023, https://doi.org/10.1016/j.ijpvp.2023.104954

- In the folder 'code' there are the core Matlab codes used in this study (data preprocessing, hyperparameter tuning, training, testing, sensitivity studies) and one code called 'brain programm' to call all the sub-programs from itself.

- In the folder 'trained_models' there are the Matlab data files with the two trained models (.mat files) and a file 'call_model'. To use the models, the user needs to open the 'call_model' file in Matlab and then load the .mat file for the model of interest (either the axial_model.mat for axial or the hoop_model.mat for hoop residual stress prediction).

For more info please contact the corresponding author Dimitra Rissaki at dimrissaki@gmail.com

Have a nice day :)
