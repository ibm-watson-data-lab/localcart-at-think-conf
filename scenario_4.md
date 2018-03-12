### Scenario: Build a revenue dashboard using PixieApps

Learn how to use streaming analytics to process and aggregate data in real-time and visualize the persisted results using a simple web app in a Python notebook.
![scenario_4](https://raw.githubusercontent.com/ibm-watson-data-lab/localcart-at-think-conf/master/images/scenario_4.png)

#### Prerequisites
 * Streaming Analytics service instance
 * Cloud Object Storage
 * IBM Data Catalog (a Watson Data Platform application)
 * PixieDust

#### Notebook preview

 * [Click to preview]()
 
#### Getting started

If you have been assigned a pre-configured user id and password:
 * Open [IBM Watson Data Platform](https://dataplatform.ibm.com/projects?context=analytics) and log in using the provided credentials.
 * Open project **8624H**.
 * In the **Assets** tab open notebook **senario-four** by clicking on the pencil icon.
 * Follow the notebook instructions
 * Note: Use the following Message Hub connection information:
    * **Name**: `clickstream` 
    * **API key**: `rtWLI3VCAhgkVo73pDCJLlc84UHfLKn326rCJERABYGL55LE`
    * **Brokers**: `kafka05-prod01.messagehub.services.us-south.bluemix.net:9093,kafka02-prod01.messagehub.services.us-south.bluemix.net:9093,kafka04-prod01.messagehub.services.us-south.bluemix.net:9093,kafka01-prod01.messagehub.services.us-south.bluemix.net:9093,kafka03-prod01.messagehub.services.us-south.bluemix.net:9093`
    * **Username**: `rtWLI3VCAhgkVo73`
    * **Password**: `pDCJLlc84UHfLKn326rCJERABYGL55LE`

If you have not been assigned a pre-configured user id and password:

 * Open [IBM Watson Data Platform](http://datascience.ibm.com/analytics)
 * [Add IBM Data catalog (Lite plan) to your Watson Data Platform](https://dataplatform.ibm.com/data/discovery?target=offerings&context=analytics)
 * [Create a new project (or re-use an existing one) and associate it with an Apache Spark service instance](https://dataplatform.ibm.com/projects?context=analytics)
 * Add a new notebook from URL https://raw.githubusercontent.com/ibm-watson-data-lab/localcart-at-think-conf/master/notebooks/localcart-scenario-four.ipynb
 * Follow the notebook instructions
