# Space-weathering-age-of-S-type-and-V-type-asteroid-families-from-the-Sloan-Digital-Sky-Survey
This repository includes data and python codes used to predict the surface age of S-type and V-type asteroid families.

**Training Data**
You can find the training data here "https://github.com/Lakshika1990/Asteroid_surface_age_prediction/tree/main/Ensemble_model/reflectance_spectra_training%26validation" This folder has raw data of the olivine, pyroxene, olivine-pyroxene mixtures, and OCs reflectance spectra. First raw give the name of the sample. The first column 'W' is wavelength in um, and the second column is reflectance.

Python_scripts This folder contains python scripts for, Eros_model_training.ipynb - Ensemble model training and saving for Eros. Itokawa_model_training.ipynb - Ensemble model training and saving for Itokawa. SW_age_Prediction_Itokawa_Eros.ipynb - Determine the SW age for Itokawa and Eros at 1AU and distance correction for SW age.

Folders "Eros_Models and "Itokawa_models"- 30 models in ".joblib" format saved after model training.

results SW_age_Eros.xlsx - predicted SW age for Eros. -0 Location No -1 Longitude 2 Latitude 3-4 Solar wind dominant SW age and std at 1AU 5-6 std for Solar wind dominant SW age and std at 1AU 7-8 Distance crrected solarwind dominant SW age and std 9-10 distance corrected micrometeorite dominant SW age and std

SW_age_Itokawa.xlsx - predicted SW age for Itokawa. 0 Location No 1 Longitude 2 Latitude 3-4 Solar wind dominant SW age and std at 1AU 5-6 std for Solar wind dominant SW age and std at 1AU 7-8 Distance crrected solarwind dominant SW age and std 9-10 distance corrected micrometeorite dominant SW age and std
