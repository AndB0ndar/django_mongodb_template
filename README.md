# django_mongodb_template

Template for creating a Django application with a MongoDB in Docker container

## Introduction

This repository is a ready-made template for creating a web application using the Django framework, MongoDB database and containerization using Docker.
If you are looking for a quick start to develop a web application that provides scalability and flexibility, then you have come to the right place.

## Requirements

This module requires the following:

* [Docker](https://www.docker.com/get-started)
* Any version of Linux or Unix OS (Recommended and Optional)

## Installation

To build an application, run on the command line:

```
docker-compose build
```

And to run the application, run:

```
docker-compose up -d
```

## Using

### Website

In this template, the web application runs on port 8000.

### Web-based MongoDB admin interface

This template also creates a web-based user inteface for MongoDB called [mongo-express](https://github.com/mongo-express/mongo-express) through port 8081.

