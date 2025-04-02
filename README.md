# Final DevOps Project

This project demonstrates a complete CI/CD pipeline implementation using GitHub Actions and OpenShift Pipelines (Tekton).

## Project Structure

- `.github/workflows/` - Contains GitHub Actions workflow definitions
- `.tekton/` - Contains Tekton pipeline and task definitions
- `src/` - Source code for the application
- `tests/` - Test files for the application

## Setup Instructions

1. Fork this repository
2. Set up OpenShift cluster access
3. Configure GitHub secrets for OpenShift credentials
4. Push changes to trigger the pipeline

## Pipeline Components

- GitHub Actions: Handles linting and testing
- Tekton: Manages deployment and cleanup tasks
- OpenShift: Hosts the application and pipeline execution

## Requirements

- Python 3.8+
- OpenShift CLI (oc)
- GitHub account with Actions enabled
- Access to an OpenShift cluster 