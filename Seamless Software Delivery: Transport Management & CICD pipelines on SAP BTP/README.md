[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2022-XP280)](https://api.reuse.software/info/github.com/SAP-samples/teched2022-XP280)

# SAP BTP - Hands-On Enblements Day - Seamless Software Delivery: Transport Management & CI/CD pipelines on SAP BTP
## Description

This repository contains the material for the SLB: SAP BTP  Hands-On Enablement Day (21.02.2025). This session is called Seamless Software Delivery: Transport Management & CI/CD pipelines on SAP BTP.

## Overview

See how you can easily combine the agility and built-in quality of continuous integration and
delivery (CI/CD) with a transport-based deployment to a productive system. Learn how to use the SAP
Continuous Integration and Delivery service with preconfigured templates and the SAP Cloud Transport
Management service for your development use cases. Both services run on SAP Business Technology
Platform with the potential to be used as the default setup for any new development project on the
platform.

## Prerequisites

To complete the exercices in this repository, please make sure that you meet the following prerequisites:

* You have an [SAP Business Technology Platform (BTP) Trial Account](https://developers.sap.com/tutorials/hcp-create-trial-account.html).
* You have an account on [GitHub](https://github.com/signup).

## 

- [Exercise 0 - Getting Started](./ex0#exercise-0---getting-started)
    - [Exercise 0.0 - Create a Copy of This Repository](./ex0#exercise-00---create-a-copy-of-this-repository)
    - [Exercise 0.1 - (Optional) Set Up a Subaccount on Your SAP BTP Trial Account](./ex0#exercise-01---optional-set-up-a-subaccount-on-your-sap-btp-trial-account)
- [Exercise 1 - Create a Job in the SAP Continuous Integration and Delivery service](./ex1#exercise-1---create-a-job-in-the-sap-continuous-integration-and-delivery-service)
    - [Exercise 1.0 - Set Up SAP Continuous Integration and Delivery](./ex1#exercise-10---set-up-sap-continuous-integration-and-delivery)
    - [Exercise 1.1 - Add Your Repository to SAP Continuous Integration and Delivery](./ex1#exercise-11-add-your-repository-to-sap-continuous-integration-and-delivery)
    - [Exercise 1.2 - (Optional) Create a Webhook](./ex1#exercise-12-optional-create-a-webhook)
    - [Exercise 1.3 - Create and Trigger a Job in SAP Continuous Integration and Delivery](./ex1#exercise-13-create-and-trigger-a-job-in-sap-continuous-integration-and-delivery)
- [Exercise 2 - Set up SAP Cloud Transport Management](./ex2#exercise-2---set-up-sap-cloud-transport-management)
    - [Exercise 2.0 - Create Target Subaccounts for Transport](./ex2#exercise-20---create-target-subaccounts-for-transport)
    - [Exercise 2.1 - Enable SAP Cloud Transport Management for Use](./ex2#exercise-21---enable-sap-cloud-transport-management-for-use)
    - [Exercise 2.2 - Set Up the Transport Landscape](./ex2#exercise-22---set-up-the-transport-landscape)
- [Exercise 3 - Extend Your CI/CD Pipeline With Additional Stages](./ex3#exercise-3---extend-your-cicd-pipeline-with-additional-stages)
    - [Exercise 3.0 - Enable Additional Unit Tests](./ex3#exercise-30---enable-additional-unit-tests)
    - [Exercise 3.1 - Enable the Release Stage](./ex3#exercise-31---enable-the-release-stage)
    - [Exercise 3.2 - Run the Pipeline Manually](./ex3#exercise-32---run-the-pipeline-manually)
    - [Exercise 3.3 - Fix the Test and Commit Changes to GitHub](./ex3#exercise-33---fix-the-test-and-commit-changes-to-github)
    - [Exercise 3.4 - Verify the Success of Your Pipeline](./ex3#exercise-34---verify-the-success-of-your-pipeline)
- [Exercise 4 - Perform imports with SAP Cloud Transport Management](./ex4#exercise-4---perform-imports-with-sap-cloud-transport-management)
    - [Exercise 4.0 - Start the Import to Your Development Subaccount](./ex4#exercise-40---start-import-into-development-subaccount)
    - [Exercise 4.1 - Check the Transport Log](./ex4#exercise-41---check-the-transport-log)
    - [Exercise 4.2 - Verify Automatic Forwarding to Next Transport Node](./ex4#exercise-42---verify-automatic-forwarding-to-next-transport-node)

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2022 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
