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
*TODO*: Write a short discription of the key steps. Remeber to include all the screenshots required to demonstrate key steps. 

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
