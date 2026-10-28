

\# # ci-cd-final-project



\## Project Name

Coursera CI/CD Final Project



\## Overview

This project demonstrates Continuous Integration and Continuous Delivery (CI/CD) using GitHub Actions, Tekton, Docker, and OpenShift Pipelines.



\## Application

A Python application that returns a greeting.



\## Technologies

\- Python

\- Git and GitHub

\- GitHub Actions

\- flake8

\- nose

\- Docker

\- Tekton

\- OpenShift Pipelines



\## GitHub Actions

The workflow is defined in `.github/workflows/workflow.yml`.



It installs dependencies, runs flake8 linting, and executes unit tests with nose.



\## Tekton Tasks

The task definitions are stored in `.tekton/tasks.yml`.



They include cleanup and nose unit-test tasks.



\## Run Locally

Install the dependencies:



&#x20;   python -m pip install -r requirements.txt



Run linting:



&#x20;   python -m flake8 app.py tests



Run tests:



&#x20;   python -m nose -v



Run the application:



&#x20;   python app.py



\## OpenShift

OpenShift deployment requires access to an OpenShift cluster configured with Tekton and persistent storage.



