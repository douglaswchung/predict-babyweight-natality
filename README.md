# predict-babyweight-natality

The goal of this project is to predict newborn babyweight. Because not all babies get the care they need, a predictive statistical model can help better understand a key factor of newborn health. We will explore the open dataset, Natality, which is available on BigQuery (https://bigquery.cloud.google.com/table/bigquery-public-data:samples.natality)

The dataset includes details about births in the US from the year 1969 up to 2008. Details include year/month/day/day of week of birth, state/location of birth, age of the mother, number of gestation weeks, weight gain of mother during pregnancy, weight in pounds of newborn, and many others.

In this workshop, we walk through the process of building a complete machine learning pipeline covering ingest, exploration, training, evaluation, deployment, and prediction. Along the way, we will discuss how to explore and split large data sets correctly using BigQuery and Cloud Datalab. The machine learning model in TensorFlow will be developed on a small sample locally. The preprocessing operations will be implemented in Cloud Dataflow, so that the same preprocessing can be applied in streaming mode as well. The training of the model will then be distributed and scaled out on Cloud ML Engine. The trained model will be deployed as a microservice and predictions invoked from a web application.

Instructions for codelab
https://codelabs.developers.google.com/codelabs/end-to-end-ml/#0

Slide deck for codelab
https://www.google.com/url?q=https://goo.gl/AHDwiV&sa=D&ust=1531241570516000&usg=AFQjCNGlalr9d16ewOJWve9l6X-ncMRUrw

Prepared by Lak Lakshmanan (www.vlakshman.com)
