#### This folder included data and R codes used to create Figure 3 and 4.

##### data folder:
- `lgtreg.x.sel.rds` --- can be opened in R/Rstuido. It stores output objects from survey::svyglm(), which estimates the propensity of being included in the target data
Note: Another input data, serosurvey data (*"NIHCOVID19AntibodySt_DATA_CODES_2020-10-27.xlsx"*), is locates at /Table1_TableS4/data/ folder

##### R folder:
- `ForestPlots.R` --- R code to create Figure 3 and Figure 4. 
- `WprevSeSp_MF.R` (Author: Mike Fay) --- R function sourced by `ForestPlots.R` to perform sensitivity and specificity adjustment.
- `PSwtEst_0.1.0.tar.gz` (Author: Yan Li) --- R package to compute prevalence estimate

##### intermediate data folder:
This folder includes output data generated from `ForestPlots.R`. Some of the output datasets were further used to create Figure 3 and 4. 
Data list:
- RemoveItemWithSmallSampleSize \_Adjusted_Prevalence_KWmethod_NotSixQuotaVariable_09Dec2020.xlsx  --- to create Figure 3
- Copy of Copy of Adjusted_Prevalence_KWmethod_SixQuotaVariable_09Dec2020.xlsx  --- to create Figure 4
- Copy of PropPositive_SimpleMethod_AllVariables_03Dec2020  --- to calculate positive numbers appeared in Figure 3 and 4





