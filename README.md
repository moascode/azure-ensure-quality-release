# Overview
This project is to create disposable test environments and run a variety of automated tests using azure devops to ensure quality release.

## Dependencies
1. Azure DevOps
2. Terraform
3. JMeter
4. Postman
5. Python
6. Selenium

## Build
* Successful execution of the pipeline

    ![Build Result](/screenshots/build_result.png)

* Log output of Terraform

    ![Terraform Log](/screenshots/terraform_log.png)

## Deploy
* Successfull deployment of FakeRestApi

    ![Webapp Deploy](/screenshots/webapp_deploy.png)

## Test
### Validation and Regression Test
* Postman: Publish Test Result step

    ![Publish Test](/screenshots/postman_publish_test.png)

* Postman: Run Summary of tests

    ![Postman Tests Summary](/screenshots/postman_tests_summary.png)

* Postman: Data Validation Test Result

    ![Data Validation Tests](/screenshots/postman_data_validation_tests.png)

* Postman: Data Regression Test Result

    ![Data Regression Tests](/screenshots/postman_data_regression_tests.png)

### UI Test
* Selenium: Successful execution of the Test Suite on VM

    ![UI Tests](/screenshots/selenium_ui_tests.png)

### Endurance and Stress Test
* JMeter: Endurance Test Run

    ![Endurance Tests](/screenshots/jmeter_endurance_tests.png)

* JMeter: Stress Test Run

    ![Stress Tests](/screenshots/jmeter_stress_tests.png)

## Logging and Monitoring
* WebApp alert rule of Http404

    ![Alert Rule](/screenshots/webapp_alert_rule.png)

* WebApp alert actiongroup of Http404

    ![Alert Action Group](/screenshots/webapp_alert_action_group.png)

* Email notification of the alert

    ![Email Alert](/screenshots/email_alert.png)

* WebApp graph of the alert

    ![WebApp Metrics](/screenshots/webapp_metrics.png)

* Log analytics of the WebApp

    ![WebApp Log Analytics](/screenshots/webapp_log_analytics.png)

* Log analytics of the Selenium Test Suite

    ![Selenium Log Analytics](/screenshots/selenium_log_analytics.png)