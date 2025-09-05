# fire-exposure-index
[fire-exposure-index.com](https://www.fire-exposure-index.com)

This repository holds 
a file to put services 
and 
a docker-compose.yml file to run all services locally

everything in /services is ignored in this repository 

## Services 
are in the /services file 
the docker compose file has 4 services 

1. PsotgresDB
2. PGAdmin 
3. API in /services/api
4. ETL Pipeline for putting data into the Database /services/data-etl


## .db.env 
file is needed to run the docker-compose.yaml file its format 
```
POSTGRES_USER=***
POSTGRES_PASSWORD=***
POSTGRES_DB=***
POSTGRES_PORT=***
POSTGRES_HOST=db

PGADMIN_DEFAULT_EMAIL=***
PGADMIN_DEFAULT_PASSWORD=***


EMAIL_NAME=***
EMAIL_PASSWORD=***

```
