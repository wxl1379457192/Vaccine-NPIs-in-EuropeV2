# Vaccine-NPIs-in-EuropeV2
Updated version of Vaccine-NPIs-in-Europe
Code.zip has the master file underlying the analysis in Ge et al: Untangling the changing impact of non-pharmaceutical interventions and vaccination on European COVID-19 trajectories. DOI:10.1038/s41467-022-30897-1 

The main_data_process.R has the main code to run the analysis. Meanwhile, you need to download stanmodel.zip. The sensitivity analysis dataprocess.R has the code for sensitivity analysis and its plotting. If you want to extract the priori and posteriori distributions of the model parameters as the supplemental figures, please download the distribution_plot.R. In addition to main_data_process.R, both fig3plot.R and forestplot.R can reproduce the figures. Note that the output figures here are meta data without embellishment. Leave-one-out-validation.R and poolingresult.R stored the code for cross-validation. 


You can get the data we used via this link or their original source mentioned in our manuscript. To ensure reproducibility of all results, we recommended wxl1379457192/Vaccine-NPIs-in-EuropeV2/ which corresponds to the data version employed in our analysis. 
