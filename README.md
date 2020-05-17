# Feature-engineering 

“ML on data model with data augmentation”

From our homes, we are seeing the very negative impact that the COVID-19 is having on all aspects within the global society.

Our group, as students of data analysis, have decided to do our bit from the point of view of data, and how it can bring value to the fight against this pandemic.

To this end, we have created a probability model with weights based on variables that provide us with useful value based on different papers and data analysis provided by official organizations. In addition, for reading data in the papers we have made Web Scraping, which allows us to update our model automatically along with the update of the papers on which we have based. Thus we avoid the manual update.

We have faced the problem of insufficient real datasets with which to train our models, so we have chosen to generate our own datasets including all possible combinations of the variables included in them.

Since the model is designed to work with real datasets, we considered highly relevant to implement a very exhaustive process to control the quality of the data.

Our model works in a simple way. Based on the papers and data analysis, we have given weights to the variables to calculate a final probability as an output, which is the target of the model. We have used this probability to classify users into three different states: not suspicious, suspicious without symptoms and suspicious with symptoms. In addition, we went even deeper, detailing the kind of severity the user might have if infected. For the severity part, we have applied this algorithm on a simulated dataset so that in the future you can learn about the real data and the variables analyzed. 

In the model we have included plots and histograms that allow us to evaluate the validity of the data studied.

The first model Contagio has the following files:

  1.Dataset_contagio_Final.ipynb
  2.first_final_infection_dataset.csv -> https://drive.google.com/file/d/1R-2h-UQUI4lo8-C5p7OisvLRqJkzyVQY/view?usp=sharing
  3.final_infection_dataset.csv -> https://drive.google.com/file/d/1-EiLWa4PJtlsbT6t-faHABYuwgMDlL3Q/view?usp=sharing
  4.Zona_riesgo_01.ipynb
  5.Risk_by_region.csv
  6.First_RandomForest_Contagio.ipynb
  7.RandomForest_Contagio.ipynb

The second model severity has the following files:

  1.Dataset_Gravedad_Final.ipynb
  2.final_severity_dataset.csv
  3.RandomForest_Gravedad.ipynb
  
Real dataset (Mexico):

  1.200502COVID19MEXICO.csv
  2.Dataset MEX ML.ipynb
  3.RandomForest Dataset MEX ML.ipynb
