# Udacity Project - Securing Recipe Vault Web App

This is one of the project in Udacity AWS Cloud Architect Nanodegree.

## Project Overview

In this project, I have:

-   Deployed and assessed a simple web application environment’s security posture
-   Tested the security of the environment by simulating attack scenarios and exploiting cloud configuration vulnerabilities
-   Implemented monitoring to identify insecure configurations and malicious activity
-   Applied methods learned in the course to harden and secure the environment
-   Designed a DevSecOps pipeline

## Project Files

-   `E1T4.md`: Text file identifying 2 poor security practices with justification for the `AWS-WebServiceDiagram-v1-insecure.png` architectural model.
-   `E2T2.md`: Text file providing recommendations on how to remediate the vulnerabilities.
-   `E3T1.md`: Text file listing GuardDuty findings that were detected related to the brute force attack ande explaination about how GuardDuty detected the attack.
-   `E4T1.md`: Text file listing 2-3 changes that can be made to environment to prevent an ssh brute force attack from the internet and also 2-3 points about how to secure the sensitive data in S3.
-   `c3-s3_solution.yml`: CloudFormation template that deploys an S3 bucket for storage of recipes woth default encryption enabled.
-   `c3-app_solution.yml`: CloudFormation template that deploys ec2 instances for the project starter. Security group rules only accept traffic from specific ports in this template.
- `screenshots`: This folder contains all the screenshots captured during this project.
