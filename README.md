# cloud-ci-lab-project
# Cloud CI Lab Project

## Overview
This project demonstrates a simple Cloud CI pipeline using GitHub Actions.  
It automates the process of running a Python application and executing tests every time code is pushed to the repository.

The project follows GitOps principles by defining the CI pipeline as code using YAML stored in the repository.

## Project Structure

cloud-ci-lab-project/
│── app.py  
│── test_app.py  
│── .github/workflows/ci.yml  
│── README.md  

## Features
- Simple Python cloud-ready application  
- Automated CI pipeline using GitHub Actions  
- Automatic build and test execution on push  
- Failure detection and debugging practice  
- Pipeline extension with additional workflow steps  

## Application

### app.py
Prints:
Cloud CI Pipeline Running

## Testing

### test_app.py
Checks that the application runs successfully.

Run locally:
python test_app.py

## CI/CD Pipeline

Workflow file location:
.github/workflows/ci.yml

Pipeline steps:
1. Checkout repository  
2. Set up Python environment  
3. Print build message  
4. Run application  
5. Run tests  

The pipeline runs automatically on every push to the `main` branch.

## How to Run Locally

python app.py  
python test_app.py  

## Learning Outcomes

- Creating a GitHub repository  
- Building a simple cloud application  
- Writing automated tests  
- Implementing CI using GitHub Actions  
- Understanding pipeline failures and debugging  
- Applying GitOps principles  


## Author
Rebecca Batoh  
Cloud Computing Lab Project
