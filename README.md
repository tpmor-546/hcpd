# hcpd
EDA and k-means clustering of human connectome project in dev behavioral data 

EDA.Rmd takes several .csv files of open access human connectome in development dataset and creates tidy data frame hcpd.Rdata.

k-means-clustering-allages.Rmd takes tody data, runs some more EDA, removes outliers in gripstrength var and runs k-means clustering of four NIH toolbox motor measures. Cluster stability is tested with bootstrapped Jaccard index and validated by testing differences in cognitive function between cluster assingment with linear mixed effect models (with random effect of data collection site). 

k-means-clustering-highschool.Rmd and k-means-clustering-middleschool.Rmd replicates k-means-clustering-allages.Rmd in age split groups per middle school and high school ages. 

plots are created in each step. 
