# DevSecOps 

## Terminologies

* SAST - Static Application Security Testing
    - White-box testing that analyzes source code for identifying security issues.

* SCA - Software Composition Analysis
    - Scans your code base to provide visibility into open source software components,<br>
      including license compliance and security vulnerabilities.

* DAST - Dynamice Application Security Testing
    - Dynamic Application Security Testing is a type of black-box security testing in which dynamic tests are performed on the application.

* IAST - Interactive Application Security Testing
    - It combines elements of both SAST and DAST and tries to overcome its limitations. It scans specific workflows of the code.

* IAC - Infrastructure as Code 
    - Identifying issues with IaaC, is known as IAC security testing.

* API Security - is also called as Security for Microservices (Microservices is a subset of API), e.g. E-Commerce Application will have User Registration API and this API will have microservices to Create/Update/Delete users.

## Tools used for implementing DevSecOps

### Development

* Git Secrets - Implemented at development phase. This notifies whether any secret has been accidentally commited onto github.
* Security Plugins - Integrate plugins to IDE to catch issues at development phase.
* TruffleHog - Similar to git secrets, comes with enterprise license.

### Security

* Code Quality Tools - Sonarqube
* SAST security Tools - Fortify, Veracode, CheckMarx
* SCA security Tools - Fortify, Veracode, Blackduck, Synk
* DAST security Tools - OWASP, ZAP, WebInspect, Veracode DAST, Acunetix
* IAC security Tools - Bridgecrew, Synk
* Container Security Tools - Aqua Qualys, Prisma Cloud

### Operations

* Build Pipeline Tools - Jenkins, AWS, GCP Cloudbuild, Azure DevOps, Github Actions, Gitlab
* Cloud Security Posture Management Tools - Aqua, BridgeCrew
* Container Registry Scanning Tools - AQUA, AWS Native Registry Scanning
* Infrastructure Scanning Tools -Chef Inspec(compliance), Nessus
* Cloud Security Tools - AWS Security Hub, AZURE Defeneder.

