[Syllabus](Syllabus.pdf)|||||||
||||||||
||||||||
|Week|Date   |Module                |Lecture Topic                                                     |Discussion                                                              |Lab                                                     |Reading                                                                                |
|----|-------|----------------------|------------------------------------------------------------------|------------------------------------------------------------------------|--------------------------------------------------------|---------------------------------------------------------------------------------------|
|    |1/21/25|Basics                |[Intro to course](lectures/Intro.pdf)                                                   |What do you want from the course?                                       |[Density-dependent population model](labs/intro2R.html) |                                                                                       |
|    |1/23/25|Basics                |[Intro to modeling approaches, philosophies, Sources of uncertainty](lectures/Lecture2.pdf)|Logistic growth model check-in, Clark et al. 2001, Houlahan et al 2017 |                                                        |[Clark et al. 2001](papers/Clark2001.pdf) | [Houlahan et al. 2017](papers/Houlahan2016.pdf)|
|    |1/28/25|Time-series approaches|Temporal autocorrelation and decomposition                        |                                                                        |[Time-series decomposition](labs/ts_decomp_autocorr.html)                              |                                                                                       |
|    |1/30/25|Time-series approaches|[Autoregressive models](lectures/ARmodels.pdf)                                             |                                                                        |[AR model forecasting](labs/ARmodel.html)|   <!--[My code](https://github.com/bobshriver/UNR-EcoForecast/blob/main/lectures/AR1model.R)-->                  |[Optional Reading: NEON working with time](https://www.neonscience.org/resources/learning-hub/tutorials/introduction-working-time-series-data-text-formats-r)                                                                 |
|    |2/4/25|Time-series approaches [Evaluating forecasts, Bias-Variance tradeoff](lectures/ModelValidation.pdf); <!--[My AR code](lectures/AR1model.R)-->                      |                                                                        |Evaluating time series forecasts [See end of lecture]                        |  Dietze Chapter 16                                                                                     |
|    |2/6/25|Building the toolbox  |[Bayesian modeling and thinking](lectures/IntroToBayes.pdf)                                   |                                                                        |                                                        |         Dietze Chapter 5| [Additional background on Bayes](https://www.youtube.com/watch?v=HZGCoVF3YvM)                                                                             |
|    |2/11/25| No Class      
|    |2/13/25|Building the toolbox  |Intro to Stan: [R code](lectures/StanSetup.R). [Stan Code](lectures/StanExample.stan)                                                   |                                                                        |[NDVI model](labs/IntroToStan.html)                           |    [Optional Reading: Stan intro]( https://ourcodingclub.github.io/tutorials/stan-intro/)                                                                                  |
|    |2/18/25|Building the toolbox  |Characterizing Uncertainty    <!--[Example code](lectures/StanSetup_Portal.R)-->                                    |                                                                        |[Parameter Uncertainty](labs/IntroToStan_2.html)                         |                                                                                       |
|    |2/20/25|Building the toolbox  |Propagating Uncertainty                                           |                                                                        |[Process Variability](labs/IntroToStan_3.html))                               |       Dietze Chapter 6 and 11                                                                                |
|    |2/25/25|                      |[Intro to Forecasting challenge #1](labs/challenge1.html)                                 |    Check in on process var lab                             |Forecasting challenge #1                                |                                                                                       |
|    |2/27/25|                      ||                                                                        |Forecasting challenge #1                                |                       Talk with Bob about [project topic/data](labs/Project.html) before 3/12. Project Report Due May 8                               |
|    |3/5/25|                    |                                                                 |                                                 | Forecasting challenge #1                                                   |                                                                                       |
|    |3/7/25|                |                                                                 |                                                 | Forecasting challenge #1      (Turn in Forecast on Webcampus)                                                |                                                                                       |
|    |3/11/25|           |       Group presentations                                                           |    Evaluating forecasts/Debrief                                                                       ||                                                                                       |
|    |3/13/25|                      |  [Model Selection](lectures/ModelSelection.pdf)    [Example regularization code](lectures/RegCode.stan)                                                       |                [Intro to Paper Discussion Assignment](labs/PaperAssignment.pdf)                        |                                                      |    [Model Selection](https://esajournals.onlinelibrary.wiley.com/doi/10.1002/ecy.3336)  [Model Ensembling](https://www.sciencedirect.com/science/article/pii/S016953470600303X?casa_token=E7l5YhfhaagAAAAA:_-WctoidjuF3bKB4Y5tSYui9mUetxllMJXeBfLUf3-qytccfE1sVNh9IbRv8lmH78PxVZqoxEBI)                                                                                  |
|    |3/18/25|  Simulation Methods for building models  [Rcode](lectures/SS/SSr.R)    |      [Stan Code Poisson](lectures/SS/StanSSPois.stan)    [Stan Code Normal](lectures/SS/StanSSNorm.stan)                                   |                                                                        |                          |                                                                                       |
|    |3/20/25|                      |                                                                  |     Weather Forecasting                                                                   |                                                         |                                  [Paper 1](https://www.science.org/doi/10.1126/science.aav7274) [Paper 2](https://www.pnas.org/doi/epdf/10.1073/pnas.1716760115)                                                 |
|    |3/25/25|Spring Break          |                                                                  |                                                                        |                               |                                                                                       |
|    |3/27/25|Spring Break            |                                                                  |                                                 |                                                        |                                                                                       |                                                                             
|    |4/1/25|                           |     [Forecasting Challenge 2](https://docs.google.com/document/d/1yba8Uy47tCvfJS3nrmyB5agzKL2i0E8Ro1yc9M9ehX4/edit)                                                |                                                              |Forecasting challenge #2                                |         |
|    |4/3/25|                      |                                                                  |                                                                        |Forecasting challenge #2                                |                                                                                    |
|    |4/8/25|                      |                                                                  |                                                                        |Forecasting challenge #2  (Turn in forecast to Webcampus)|                                                                            |
|    |4/10/25|                      |       Group presentations                                                           |    Evaluating forecasts/Debrief                                                                       ||                                                                            |
|    |4/15/25|                      |                                                                  |                                                                        |                        Paper discussion ([see spreadsheet](https://docs.google.com/spreadsheets/d/1bsSFoy_DIFoCZK40wD9my73sO2WA6TU5F_RLr9w4lRE/edit#gid=0))/ Final Project                                    |                                                          |
|    |4/17/25|                      |                                                                  |                                                                        |                             Paper discussion ([see spreadsheet](https://docs.google.com/spreadsheets/d/1bsSFoy_DIFoCZK40wD9my73sO2WA6TU5F_RLr9w4lRE/edit#gid=0))/ Final Project                               |                                                               |
|    |4/22/25|                      |                                                                  |                                                                        |                          Paper discussion ([see spreadsheet](https://docs.google.com/spreadsheets/d/1bsSFoy_DIFoCZK40wD9my73sO2WA6TU5F_RLr9w4lRE/edit#gid=0))/ Final Project                                  |                                                                  |
|    |4/24/25|                      |                                                                  |                                                                        |                         Paper discussion ([see spreadsheet](https://docs.google.com/spreadsheets/d/1bsSFoy_DIFoCZK40wD9my73sO2WA6TU5F_RLr9w4lRE/edit#gid=0))/ Final Project                                   |                                                                                |
|    |4/29/25|                      |                                                                  |                                                                        |                        Final Project                                   |                                                                        |
|    |5/1/25|                      |                                                                  |                                                                        |                       Final Project                                 |                                                                                   |
|    |5/6/25|                      |                                                                  |                                                                   |                                   Presentations  (Report due May 9)                   |                                                                                       |
                                                                          |
