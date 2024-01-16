# Machine Learning Production Model for Bank Marketing dataset
Use Azure to configure a cloud-based machine learning production model utilizing the [Bank Marketing dataset](https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv), deploy the best model, and consume it. Also create, publish, and consume a pipeline. 

## Architectural Diagram
![Architecture Diagram](../sample_screenshots/arch_diagram.png)
* Authentication (optional) - Create a Service Principal account and associate it with the workspace. Not authorized with Udacity access.
* Auto ML experiment - upload Dataset, create compute cluster, use Auto ML classification and define parameters
* Deploy the best model - Post completion of the Auto ML experinment, deploy the best mode
* Enable logging -  - Enable application insights
* Swagger Documentation - Swagger setup to view API details
* Consume model endpoint - Consume model endpoint, perform benchmarking
* Create and publish a pipleline - standardize the best practices of producing a machine learning model, enables execution at scale, and improves the model building efficiency
* Documentation - Finish documentation

## Key Steps
* Create a new Auto ML experiment
* Create Dataset in Azure
  ![Bank Marketing dataset](../sample_screenshots/Banktraining%20Dataset.png)
* Create a new compute cluster (aml_compute)
* Auto ML experiment complete
  ![Auto ML experiment](../sample_screenshots/AutoML%20Experiment.png)
* Best model - Voting Ensemble
  ![Best model](../sample_screenshots/Best%20Model.png)
* Best model - stats
  ![Best model stats](../sample_screenshots/Best%20Model%20Stats.png)
* Deploy the best model, enable logging and application insights
  ![Logging](../sample_screenshots/logspy.png?raw=true)
  ![Model endpoint with application insghts](../sample_screenshots/Application%20Insights.png)
* Setup Swagger for the APIs
  ![Swager](../sample_screenshots/Swagger.png)
* Consume Model endpoints
  ![Model Endpoints, 2 results](../sample_screenshots/Endpoint.png)
* AB Benchmarking
  ![AB benchmarking](../sample_screenshots/Benchmark.png)
* Create and publish a pipeline
  ![Create a pipeline](../sample_screenshots/Pipeline.png)

  Azure ML Pipeline
  ![Azure ML Pipeline](../sample_screenshots/AzureML%20Scheduled%20Run.png)
  ![Azure ML Pipeline](../sample_screenshots/Dataset%20within%20AutoML.png?raw=true)
  
  Pipeline Completed
  ![Pipeline completed](../sample_screenshots/Pipeline%20Complete.png)

  Notebook - Run Details
  ![Pipeline run details](../sample_screenshots/NB%20Run%20Details.png)

  Published Pipeline overview
  ![Published pipeline overview](../sample_screenshots/Published%20Pipeline%20Overview.png?raw=true)
  
  Pipeline Jobs
  ![Pipeline jobs](../sample_screenshots/Pipeline%20Jobs.png)

  Pipeline run details
  ![Run details](../sample_screenshots/NB%20Run%20Details%20Step%20Run.png)

  Pipeline run details - Azure ML Studio
  ![Pipeline run details](../sample_screenshots/ML%20Studio%20Pipeline%20Run.png)

  
## Screen Recording
Please download/ view the mp4 screen recording from:
[Screen Recording](https://github.com/raman340/uda_project2/blob/master/starter_files/Project%202.mp4)

## Standout Suggestions
* Dataset analysis: Data Imbalance was detected due to higher number of no values as compared to yes
  ![Class imbalance](../sample_screenshots/Data%20Imbalance.png)

* Dataset: Top 4 features
  ![Top 4 features](../sample_screenshots/Top%204%20Features.png?raw=true)
