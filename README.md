# demo-cicd-cosmosdb-restapi

Contains reference implementation of doing a document-leve insert in an azure pipeline. The key components are:

- **azure-pipeline.yml** - Release pipeline that executes create-document script.
- **create-document.sh** - Bash script that uses az rest cli to make CosmosDB REST API call.
 
