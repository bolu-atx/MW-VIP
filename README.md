## MW-VIP
moving window variable importance in projection feature selection technique for partial least square regression

### Why another feature selection technique if I can use LASSO / Sparse PLS / etc.

The common variable selection techniques for PLS variable selection assume that only one operating mode exists in the data. This is not a valid assumption for applications where multiple operating points are present. The MW-VIP method exploits the time dependency of process data to maximize the selection of relevant variables in each operating mode. Tuning parameters of moving window size and percentile value can be used to tune the sensitivity of the MW-VIP method to local correlations. To evaluate the selection candidate models, four types of performance criteria were proposed. In addition to model performance, model parsimony can be assessed by calculating the AIC of each model. The residual distribution shift score was developed as an indicator for testing the robustness of candidate models. Lastly, the process monitoring T2 ratio yields information on the sensitivity of model prediction quality to excursions and abnormalities in process data. These four types of evaluation criteria combined can be used to improve the assessment of model performances and variable selection results. Modeling results from the simulated case study and the industrial data set show that the moving window PLS produced a better model than SwPA, VIP filtering and sparse PLS selection methods. To better deal with colinearity in large data sets, future work on the MW-VIP method will investigate substituting the standard PLS algorithm in MW-VIP with sparse PLS to achieve simultaneous variable selection and sparse VIP calculation.

## References
 http://www.sciencedirect.com/science/article/pii/S0169743914000689

Industrial PLS model variable selection using moving window variable importance in projection
Bo Lu, Ivan Castillo, , Leo Chiang, Thomas F. Edgar
