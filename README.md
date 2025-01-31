This folder contains files to support the chapter "Computational methods for efficient fitting of ODE models to time series data using pomp."  by Kathryn Montovan, Eli Goldwyn, Julie Blackwood, and Aaron A. King

There are rmd, csv, and pdf files. The rmd files should be used in combination with the chapter while you explore the 
presented model and can be modified to make your own model. The csv files are datasets you will use in the model or
may want to use in your project. We include knit pdf files for each of the rmd model files so that you can see what results 
you get (roughly) from each file. This can both be helpful for troubleshooting and for understanding what the files are doing. 

Files:

SimulatedSIRdata.csv  Observations of recorded new infections of "pompitis" - used in all the following model files                     

*Model 1 SI.Rmd________The model that most of the chapter explains formatted for learning the method. Use this file as you read the chapter. 

*Model 2 SIR.Rmd_______This second model is formatted more like you might want to for your own project. Use this file to run the second model in the chapter and modifyt it to create your own model and project. 

*Model 3 SIR with Covar.Rmd (and pdf)______Example model setup and simualtion for a model with covariate data
*****Covariate.csv_________________________The covariate data for the deathrate for people infected with "pompitis"

*Model 4 SIR time varying.Rmd (and pdf)____Example model setup and simulation for a model that depends on time (seasonality)

1918TompkinCountyNYFluDeaths.csv___________A dataset refered to in the projects. You can use it for a project if you would like. 
