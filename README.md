MySQL Replicate Cloud Project

This project aims to demonstrate MySQL database replication using a virtual machine running Ubuntu LTS 22.04 and leveraging Docker Compose to set up MySQL containers.
Project Overview

MySQL replication is a technique that allows you to create multiple copies of a MySQL database and keep them in sync with each other. This project utilizes Docker Compose to set up two MySQL containers: a master container and a slave container. Changes made to the master database will be automatically replicated to the slave database.
Prerequisites

Before getting started with this project, ensure that you have the following prerequisites installed:

    Docker: Installation Guide
    Docker Compose: Installation Guide
    MySQL [Installation Guide](https://www.cyberciti.biz/faq/installing-mysql-server-on-ubuntu-22-04-lts-linux/)

Getting Started

Clone the project repository:
