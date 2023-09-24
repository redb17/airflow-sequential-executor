# Dockerfile for Airflow (Sequential Executor)

```sh
docker build --progress=plain -t properbinaries/airflow-sequential-executor:1.0.0 -f ./Dockerfile.airflow .
# 
# or pull from Dockerhub
docker pull properbinaries/airflow-sequential-executor:1.0.0

# start container
docker container run -it --rm -p 8080:8080 properbinaries/airflow-sequential-executor:1.0.0 /bin/bash
```
