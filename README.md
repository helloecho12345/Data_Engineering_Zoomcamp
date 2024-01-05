# Data Engineering Zoomcamp

### Following DataTalks Data Engineering Zoomcamp: 
https://github.com/DataTalksClub/data-engineering-zoomcamp


* [Data Engineering Zoomcamp 2024 - Pre-Launch Q&A](https://www.youtube.com/watch?v=91b8u9GmqB4)

## Week 1

### Introduction

* [Video](https://www.youtube.com/watch?v=-zpVha7bw5A)
* [Slides](https://www.slideshare.net/AlexeyGrigorev/data-engineering-zoomcamp-introduction)
* Overview of [Architecture](https://github.com/DataTalksClub/data-engineering-zoomcamp#overview), [Technologies](https://github.com/DataTalksClub/data-engineering-zoomcamp#technologies) & [Pre-Requisites](https://github.com/DataTalksClub/data-engineering-zoomcamp#prerequisites)


#### Docker

* [Introduction to Docker](https://www.youtube.com/watch?v=EYNwNlOrpr0&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Why do we need Docker
  * Creating a simple "data pipeline" in Docker
* [Ingesting NY Taxi Data to Postgres](https://www.youtube.com/watch?v=2JM-ziJt0WI&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Running Postgres locally with Docker
  * Using `pgcli` for connecting to the database
  * Exploring the NY Taxi dataset
  * Ingesting the data into the database
  * **Note** if you have problems with `pgcli`, check [this video](https://www.youtube.com/watch?v=3IkfkTwqHx4&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
    for an alternative way to connect to your database
* [Connecting pgAdmin and Postgres](https://www.youtube.com/watch?v=hCAIVe9N0ow&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * The pgAdmin tool
  * Docker networks
* [Putting the ingestion script into Docker](https://www.youtube.com/watch?v=B1WwATwf-vY&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Converting the Jupyter notebook to a Python script
  * Parametrizing the script with argparse
  * Dockerizing the ingestion script
* [Running Postgres and pgAdmin with Docker-Compose](https://www.youtube.com/watch?v=hKI6PkPhpa0&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Why do we need Docker-compose
  * Docker-compose YAML file
  * Running multiple containers with `docker-compose up`
* [SQL refresher](https://www.youtube.com/watch?v=QEcps_iskgg&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Adding the Zones table
  * Inner joins
  * Basic data quality checks
  * Left, Right and Outer joins
  * Group by
* Optional: If you have some problems with docker networking, check [Port Mapping and Networks in Docker](https://www.youtube.com/watch?v=tOr4hTsHOzU&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
  * Docker networks
  * Port forwarding to the host environment
  * Communicating between containers in the network
  * `.dockerignore` file
* Optional: If you are willing to do the steps from "Ingesting NY Taxi Data to Postgres" till "Running Postgres and pgAdmin with Docker-Compose" with Windows Subsystem Linux please check [Docker Module Walk-Through on WSL](https://www.youtube.com/watch?v=Mv4zFm2AwzQ)
