# Overview
This project is to create disposable test environments and run a variety of automated tests using azure devops to ensure quality release.

## Dependencies
- Azure DevOps
- Terraform
- JMeter
- Postman
- Python
- Selenium

## Setting Up Dev Environment
### Log output of Terraform

## Build
### screenshot of the successful execution of the pipeline (/_build/results?buildId={id}&view=results)

## Deploy

## Test
### Postman: Run Summary page (which contains 4 graphs)
### Postman: Test Results page (which contains the test case titles from each test)
### Postman: Publish Test Results step

### Selenium: screenshot of the successful execution of the Test Suite on a VM

### JMeter: log output of JMeter when executed by the CI/CD pipeline (start with “summary” and “Starting standalone test @”)

## Logging and Monitoring
### Screenshots of the email received when the alert is triggered
###  the graphs of the resource that the alert was triggered for (be sure to include timestamps for the email and the graphs)
### the alert rule, which will show the resource, condition, action group, alert name, and severity
### Screenshots of log analytics queries and result sets
The result set will include the output of the execution of the Selenium Test Suite

## Suggestions and Corrections
Feel free to submit PRs to this repo should you have any proposed changes. 
