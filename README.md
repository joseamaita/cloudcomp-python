# Guide for Web Deployment with Python

## Introduction

### What is deployment means?

This process involves packaging up your web application and putting it 
in a production environment that can run the app.

### Why is deployment necessary?

Your web application must live somewhere other than your own desktop or 
laptop. A production environment is the canonical version of your 
current application and its associated data.

## Hosting options

There are four options for deploying and hosting a web application:

* "Bare metal" servers
* Virtualized servers
* Infrastructure-as-a-service
* Platform-as-a-service

The first three options are similar. The deployer needs to provision one 
or more servers with a Linux distribution. System packages, a web 
server, WSGI server, database and the Python environment are then 
installed. Finally the application can be pulled from source and 
installed in the environment.
