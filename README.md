# AWS DynamoDB Python Samples

## DynamoDB 

Amazon DynamoDB is a fully managed NoSQL database

## Setting up DynamoDB in Local

* Install [Docker Desktop](https://docs.docker.com/desktop/install/windows-install/)

* Run the command `docker pull amazon/dynamodb-local:latest` to download DynamoDB docker image

* If you are starting DynamoDB for the 1st time, run the command `docker run -p 8000:8000 --name dynamo-local amazon/dynamodb-local`. 
Else, you can use `docker start dynamo-local` to start DynamoDB container

* To stop DynamoDB container, `docker stop dynamo-local` 

* Install [NoSQL Workbench](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/workbench.settingup.html)

## Accessing DynamoDB using Python

### Boto3

Boto3 is SDK written in Python to access Amazon Web Services. It is been developed & maintained by Amazon

### Accessing DynamoDB with Boto3
 
* Create DynamoDB Table
* Insert item in DynamoDB Table
* Insert bulk of items in DynamoDB Table
* Update item in DynamoDB Table
* Update bulk of items in DynamoDB Table
* Select items from DynamoDB Table
* Delete item from DynamoDB Table
* Delete bulk of items from DynamoDB Table

### Accessing DynamoDB with PartiQL queries in Python

* Create DynamoDB Table using PartiQL
* Insert item in DynamoDB Table using PartiQL
* Insert bulk of items in DynamoDB Table using PartiQL
* Update item in DynamoDB Table using PartiQL
* Update bulk of items in DynamoDB Table using PartiQL
* Select items from DynamoDB Table using PartiQL
* Delete item from DynamoDB Table using PartiQL
* Delete bulk of items from DynamoDB Table using PartiQL
