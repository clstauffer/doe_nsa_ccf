# doe_nsa_ccf
Data used in Stauffer, Tan, and Matrosov (in prep, GRL)

The netcdf files are the single layer mixed phase stratiform cloud dataset by year

The ``CCF'' directory contains the statistics of the multiple linear regression used in the cloud controlling factor analysis:
- sub-directory names correspond to different combinations of variables corresponding to Table S10-S14
- file name stem: model_diags_[subdirectory]_[variable]__year_[selection].csv
- [variable]: the predicted variable of interest
- [variable_selection]: options are "sel" or "all"; "sel" is used in the manuscript
