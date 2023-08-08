These scrips are provided for reproducibility of a rice imaging study that aimed to understand whether ground-reference rice trait data could be predicted from hyperspectral imaging (HSI) data. Pipelines for each scrip are generally the same with standard output of IDs of calibration and validation datasets, ground-reference trait distribution, selected wavelengths, number of components for PLSR model, model calibration and validation results and residuals plots. Every scrip is accompanied with a pdf file, except for traits that could not be developed with PLSR models (The authors found carbon and Jmax on Week 13 unpredictable. However, it is possible for readers to run into situation that a PLSR model could not be developed for a trait. The trait typically had poor model performance as shown in the pdf file provided here). Note that model metrices may vary due to random sampling. 

Ground-reference and HSI data could be retrieved at [ https://purr.purdue.edu/publications/4079/1 ]. The file names are explained below:

A_200wv_sideviewA: Predict carbon assimilation with 200 wavelengths from sideview HSI data.

CN_400wv_sideviewA: Predict carbon to nitrogen ratio with 400 wavelengths from sideview HSI data.

CN_300wv_IND_model: Predict carbon to nitrogen ratio with 300 wavelengths using Indica subpopulation for calibration.

CN_300wv_N1_model: Predict carbon to nitrogen ratio with 300 wavelengths using high nitrogen treatment (N1) for calibration.

CN_300wv_N2_model: Predict carbon to nitrogen ratio with 300 wavelengths using low nitrogen treatment (N2) data for calibration.

CN_300wv_TRJ_model: Predict carbon to nitrogen ratio with 300 wavelengths using Tropical japonica subpopulation for calibration.

C_no_sideviewA: Predict carbon from sideview HSI data--model could not be developed.

Jmax_W13_no _sideviewA: Predict Jmax on Week 13 from sideview HSI data--model could not be developed.

Jmax_W9_200wv_sideviewA: Predict Jmax on Week 9 with 200 wavelengths from sideview HSI data.

N_400wv_sideviewA: Predict nitrogen with 400 wavelengths from sideview HSI data.

N_300wv_IND_model: Predict nitrogen with 300 wavelengths using Indica subpopulation for calibration.

N_300wv_N1_model: Predict nitrogen with 300 wavelengths using high nitrogen treatment (N1) for calibration.

N_300wv_N2_model: Predict nitrogen with 300 wavelengths using low nitrogen treatment (N2) for calibration.

N_300wv_TRJ_model: Predict nitrogen with 300 wavelengths using Tropical japonica subpopulation for calibration.

SLA_300wv_sideviewA: Predict specific leaf area with 300 wavelengths from sideview HSI data.

SLA_C_400wv_sideviewA: Predict specific leaf area with respect to carbon with 400 wavelengths from sideview HSI data.

Vcmax_W13_500wv_sideviewA: Predict Vcmax on Week 13 with 500 wavelengths from sideview HSI data.

Vcmax_W9_200wv_sideviewA: Predict Vcmax on Week 9 with 200 wavelengths from sideview HSI data.

log_E_200wv_sideviewA: Predict log-transformed evaporation with 200 wavelengths from sideview HSI data.

log_SLN_200wv_sideviewA: Predict log-transformed specific leaf nitrogen with 200 wavelengths from sideview HSI data.

log_gsw_90wv_sideviewA: Predict log-transformed stomatal conductance with respect to water with 90 wavelengths from sideview HSI data.

norm_FB_300wv_sideviewA: Predict normalized final biomass with 300 wavelengths from sideview HSI data.

norm_mQY_300wv_sideviewA: Predict normalized midday quantum yield with 300 wavelengths from sideview HSI data.

norm_pQY_200wv_sideviewA: Predict normalized pre-dawn quantum yield with 200 wavelengths from sideview HSI data.




