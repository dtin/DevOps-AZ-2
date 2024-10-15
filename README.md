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
### Architectural Diagram
![diagram](https://github.com/user-attachments/assets/441162f8-dc3c-4604-b3ab-9b6f4447d88a)
* Generate the SSH key and add to the Github. Then cloned the project in Github into Azure Cloud Shell using SSH.
![clone-source-ssh](https://github.com/user-attachments/assets/8c6d699a-955f-4225-ba70-7436687c8c24)

* Passing tests that are displayed after running the `make all` command from the `Makefile`
![test-lint-simple-app](https://github.com/user-attachments/assets/d9694549-8e00-47c0-ad07-bd787a0d6ed8)

* Github Action result for checking lint and testing the app
![github-action-check-lint-ci](https://github.com/user-attachments/assets/cf713362-45f9-4280-ba2b-72ea299998d6)

* Result when the application is running successfully on Azure Web App
![output_app_run](https://github.com/user-attachments/assets/212f6e0f-fef1-4a72-b389-75e385958338)

* Output of a test run
![test-lint-simple-app](https://github.com/user-attachments/assets/d9694549-8e00-47c0-ad07-bd787a0d6ed8)

* Automatically deploying the project to Azure App Service via Azure Pipelines and ensuring a successful deployment.
![github-action-run-app-predict](https://github.com/user-attachments/assets/ceaa8751-c217-4fcf-b19b-ba5b4bdc9def)
![azure_pipeline-run-app-predict](https://github.com/user-attachments/assets/76331551-81a8-4e71-8357-abda97bf8c1c)
![result-azure-pipeline-app-predict](https://github.com/user-attachments/assets/8599838a-c21d-48ca-8963-af5d7ed539aa)

* Successful prediction from deployed flask app in Azure Cloud Shell.
![make_predict](https://github.com/user-attachments/assets/dda37bf4-f8f8-4497-8218-5d65fd3d61f3)

* Output of streamed log files from deployed application
![project_running_AZ_portal](https://github.com/user-attachments/assets/dc4783c7-e8b9-45a2-ab2a-4533a62ded37)
![output_log_app](https://github.com/user-attachments/assets/62415306-886f-4d11-9b00-84896d2080cb)
![log_run_predict](https://github.com/user-attachments/assets/5a025eef-e210-4c11-950c-1ae393c2457a)

> 

## Enhancements

- Create a UI application for user to easy interact with data
- Research and add more datasets to improve the quality of the result

## Demo 

https://youtu.be/2lRPKkXGqf8


