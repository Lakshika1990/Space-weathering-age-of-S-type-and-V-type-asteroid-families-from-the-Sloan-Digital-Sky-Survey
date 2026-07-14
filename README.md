# Space-weathering-age-of-S-type-and-V-type-asteroid-families-from-the-Sloan-Digital-Sky-Survey
This repository includes data and python codes used to predict the surface age of S-type and V-type asteroid families.

**Training Data**
You can find the training data here "https://github.com/Lakshika1990/Asteroid_surface_age_prediction/tree/main/Ensemble_model/reflectance_spectra_training%26validation" This folder has raw data of the olivine, pyroxene, olivine-pyroxene mixtures, and OCs reflectance spectra. First raw give the name of the sample. The first column 'W' is wavelength in um, and the second column is reflectance.

Python_scripts This folder contains python scripts for, MOdel_training_and_validation.ipynb - model training and saving. Load_moedl_and_prediction.ipynb - Determine the SW agefor asteroids, and Distance_correction.ipynb -  distance correction for SW age.

Model "svr_slit_pipeline.pkl" saved after model training.

SDSS_SVR_slit_SWage_all_fil.xlsx - predicted SW age for S-type asteroids. -0 Asteroid number -1 Asteroid taxonomy -2 Proper semi-major axis -3 Proper eccentricity -4 Proper sini -5 Proper magnitude -6 Predicted SW age at 1 AU -7 Distance corrected SW age -8 Reflectance at r band -9 Reflectance at i band -10 Reflectance at z band.
SDSS_SVR_V_slit.xlsx - predicted SW age for V-type asteroids. -0 Asteroid number -1 Asteroid taxonomy -2 Proper semi-major axis -3 Proper eccentricity -4 Proper sini -5 Proper magnitude -6 Predicted SW age at 1 AU.

SW_age_Itokawa.xlsx - predicted SW age for Itokawa. 0 Location No 1 Longitude 2 Latitude 3-4 Solar wind dominant SW age and std at 1AU 5-6 std for Solar wind dominant SW age and std at 1AU 7-8 Distance crrected solarwind dominant SW age and std 9-10 distance corrected micrometeorite dominant SW age and std
