### API-M simple deployment with WSO2 DAS ###

Following instructions will help you to setup the deployment

 Execute ``` docker-compose up -d ```

This will setup 

* A mysql server (container) with apimdb / userdb / regdb
* API-Manager runs on its own in a container (store/publisher/km/gateway all in one JVM)
* A container with DAS and configured for API statistics

