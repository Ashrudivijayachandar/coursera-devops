# OpenShift Pipeline Project

## Project Name
OpenShift CI/CD Pipeline Application

## Project Description
This project demonstrates an OpenShift pipeline for source code retrieval, code quality checks, testing, container image building, and application deployment.

## Pipeline Steps
1. cleanup
2. git-clone
3. flake8/eslint
4. nose/jest
5. buildah
6. deploy/openshift-client

## Application Details
- **Platform:** Red Hat OpenShift
- **Application Port:** 8000
- **Application Status Message:** SERVICERUNNING
