# Lab 8 - CST8915 Full-stack Cloud-native Development: Deploying and Managing the Algonquin Pet Store

## Youtube Link
https://youtu.be/TKJHTVzEA84

## Azure services that could replace MongoDB and RabbitMQ
We can replace MongoDB with Azure CosmosDB as the database storage for order history in the Algonquin Pet Store app. CosmosDB is a good fit because it can be integrated into the AKS environment seamless using Azure API and it can only host the MongoDB without any changes.

We can replace RabbitMQ with Azure Service Bus as the queue/message service. This is a good fit because we can integrate it with the AKS environment easily and it can also scale better and handle more demand.
