# Overview
[![Python application test with Github Actions](https://github.com/dtin/DevOps-AZ-2/actions/workflows/pythonapp.yml/badge.svg?branch=master)](https://github.com/dtin/DevOps-AZ-2/actions/workflows/pythonapp.yml)


In this project, we will create a GitHub repository from scratch and establish a framework for both Continuous Integration (CI) and Continuous Delivery (CD).

We will use GitHub Actions along with a Makefile, requirements.txt, and application code to run initial checks, tests, and installations. We will also connect Azure Pipelines to allow Continuous Delivery to Azure App Service. The project will use Azure Cloud Shell as well.

## Project Plan
Trello Board
https://trello.com/b/rqmyeBlG/project-2-sprint-board

Original Plan
https://docs.google.com/spreadsheets/d/11w04z5g5CMs7g_lvFfPv23Uvaczb8iA6/edit?usp=sharing&ouid=109032874588359911580&rtpof=true&sd=true

Final Plan
https://docs.google.com/spreadsheets/d/1wcakM6U3c7ssLOHxj1NcN6v9_Fe89Jmk/edit?usp=sharing&ouid=109032874588359911580&rtpof=true&sd=true



## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service

* Project cloned into Azure Cloud Shell

* Passing tests that are displayed after running the `make all` command from the `Makefile`

* Output of a test run

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

> 

## Enhancements

- Create a UI application for user to easy interact with data
- Research and add more datasets to improve the quality of the result

## Demo 

https://youtu.be/2lRPKkXGqf8


