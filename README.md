MySQL Replicate Cloud Project

This project aims to demonstrate MySQL database replication using a virtual machine running Ubuntu LTS 22.04 and leveraging Docker Compose to set up MySQL containers.
Project Overview

MySQL replication is a technique that allows you to create multiple copies of a MySQL database and keep them in sync with each other. This project utilizes Docker Compose to set up two MySQL containers: a master container and a slave container. Changes made to the master database will be automatically replicated to the slave database.
Prerequisites

Before getting started with this project, ensure that you have the following prerequisites installed:

    Docker: https://docs.docker.com/get-docker/
    Docker Compose: https://docs.docker.com/compose/
    MySQL https://www.cyberciti.biz/faq/installing-mysql-server-on-ubuntu-22-04-lts-linux/

Getting Started

1 Clone the project repository:
    git clone https://github.com/your-username/mysql-replicate.git

2 Change into the project directory:
    cd mysql-replicate


3 Create a Docker Compose configuration file:
    pluma docker-compose.yml


4 Open docker-compose.yml using a text editor and add the following configuration:

5 Save and close the docker-compose.yml file.

6 Start the containers using Docker Compose:
    docker-compose up -d


   

