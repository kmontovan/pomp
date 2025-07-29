This folder contains files to support the chapter "Computational methods for efficient fitting of ODE models to time series data using pomp."  by Kathryn Montovan, Julie Blackwood, Eli Goldwyn, and Aaron A. King

There are rmd, csv, and pdf files. The rmd files should be used in combination with the chapter while you explore the 
presented model and can be modified to make your own model. The csv files are datasets you will use in the model or
may want to use in your project. We include knit pdf files for each of the rmd model files so that you can see what results 
you get (roughly) from each file. This can both be helpful for troubleshooting and for understanding what the files are doing. 

Model Files:

*Model 1 SI.Rmd (and pdf): The model that most of the chapter explains formatted for learning the method. Use this file as you read the chapter. 

*Model 2 SIR.Rmd (and pdf): This second model is formatted more like you might want to adapt for your own project. Use this file to run the second model in the chapter and later you can use copy and modify it to create your own model for your project. 

*Model 3 SIR with Covar.Rmd (and pdf): Example setup and simualtion for a model with covariate data

*Model 4 SIR time varying.Rmd (and pdf): Example setup and simulation for a model that depends on time (seasonality)

*Npdependency.Rmd (and pdf): A file which shows how you can explore the effects of different choices of $Np$ on your results. 

*R_Csnippets.Rmd (and pdf): A file which can help with troubleshooting the switch from R code to Csnippets. 

Datasets: 

SimulatedSIRdata.csv  Observations of recorded new infections of "pompitis" - used in all the following model files                     

**Covariate.csv: The covariate data for the deathrate for people infected with "pompitis"

1918TompkinCountyNYFluDeaths.csv: A dataset refered to in the projects. You can use it for a project if you would like. 
