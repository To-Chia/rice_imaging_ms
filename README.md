These scripts are associated with the manuscript:

Ting T, Souza A, Imel R. K., Guadagno C. R., Hoagland C., Yang Y., and Wang D. R. Quantifying physiological trait variation with automated hyperspectral imaging in rice. In revision, _Frontiers in Plant Science_ 

Pipelines in each script are set up similarly with standard output of IDs of calibration and validation datasets, ground-reference trait distributions, selected wavelengths, number of components for PLSR models, results of model model calibration and validation and plots of residual. Every script (RMD file) is accompanied by a PDF file, except for traits that could not be developed with PLSR models (see above reference). Note that model metrics may vary due to random sampling and annotations of %RMSEP on plots were based on the time the authors ran the code.


Ground-reference and HSI data may be retrieved at [ https://purr.purdue.edu/publications/4079/1 ]. The file names are explained below:

A_200wv_sideviewA.Rmd: Predict carbon assimilation with 200 wavelengths from sideview HSI data.

CN_400wv_sideviewA.Rmd: Predict carbon to nitrogen ratio with 400 wavelengths from sideview HSI data.

CN_300wv_IND_model.Rmd: Predict carbon to nitrogen ratio with 300 wavelengths using Indica subpopulation for calibration.

CN_300wv_N1_model.Rmd: Predict carbon to nitrogen ratio with 300 wavelengths using high nitrogen treatment (N1) for calibration.

CN_300wv_N2_model.Rmd: Predict carbon to nitrogen ratio with 300 wavelengths using low nitrogen treatment (N2) data for calibration.

CN_300wv_TRJ_model.Rmd: Predict carbon to nitrogen ratio with 300 wavelengths using Tropical japonica subpopulation for calibration.

C_no_sideviewA.Rmd: Predict carbon from sideview HSI data--model could not be developed.

Jmax_W13_no _sideviewA.Rmd: Predict Jmax on Week 13 from sideview HSI data--model could not be developed.

Jmax_W9_200wv_sideviewA.Rmd: Predict Jmax on Week 9 with 200 wavelengths from sideview HSI data.

N_400wv_sideviewA.Rmd: Predict nitrogen with 400 wavelengths from sideview HSI data.

N_300wv_IND_model.Rmd: Predict nitrogen with 300 wavelengths using Indica subpopulation for calibration.

N_300wv_N1_model.Rmd: Predict nitrogen with 300 wavelengths using high nitrogen treatment (N1) for calibration.

N_300wv_N2_model.Rmd: Predict nitrogen with 300 wavelengths using low nitrogen treatment (N2) for calibration.

N_300wv_TRJ_model.Rmd: Predict nitrogen with 300 wavelengths using Tropical japonica subpopulation for calibration.

SLA_300wv_sideviewA.Rmd: Predict specific leaf area with 300 wavelengths from sideview HSI data.

SLA_C_400wv_sideviewA.Rmd: Predict specific leaf area with respect to carbon with 400 wavelengths from sideview HSI data.

Vcmax_W13_500wv_sideviewA.Rmd: Predict Vcmax on Week 13 with 500 wavelengths from sideview HSI data.

Vcmax_W9_200wv_sideviewA.Rmd: Predict Vcmax on Week 9 with 200 wavelengths from sideview HSI data.

log_E_200wv_sideviewA.Rmd: Predict log-transformed evaporation with 200 wavelengths from sideview HSI data.

log_SLN_200wv_sideviewA.Rmd: Predict log-transformed specific leaf nitrogen with 200 wavelengths from sideview HSI data.

log_gsw_90wv_sideviewA.Rmd: Predict log-transformed stomatal conductance with respect to water with 90 wavelengths from sideview HSI data.

norm_FB_300wv_sideviewA.Rmd: Predict normalized final biomass with 300 wavelengths from sideview HSI data.

norm_mQY_300wv_sideviewA.Rmd: Predict normalized midday quantum yield with 300 wavelengths from sideview HSI data.

norm_pQY_200wv_sideviewA.Rmd: Predict normalized pre-dawn quantum yield with 200 wavelengths from sideview HSI data.




