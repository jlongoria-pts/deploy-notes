# Notes on Deployment Issues

The most critical issue is described in [FB 177792](https://teams360.fogbugz.com/f/cases/177792/Dashboard-deployment-process-capitalizes-the-words-in-the-report-name-on-JasperServer).

In short, the deployment process succeeds in uploading the report to JasperServer but it does so with an incorrect resource ID.

Deployment has been tested using both the [report deployer tool](https://update.teams360.net/operations/report.html) and the _Jasper Custom Reports_ entry point. Below is a summary of which steps in the deployment process are succeeding or failing for each method:

## Deployer Tool

* PD
	- [x] Report profile is created.
  - [x] Stored procedure is inserted.
  - [ ] Dashboard uploaded to JasperServer
  - [ ] Dashboard has correct resource ID
  
* TR
  - [x] Report profile is created.
  - [x] Stored procedure is inserted.
  - [x] Dashboard uploaded to JasperServer
  - [ ] Dashboard has correct resource ID
  
* CV
  - [x] Report profile is created.
  - [x] Stored procedure is inserted.
  - [x] Dashboard uploaded to JasperServer
  - [ ] Dashboard has correct resource ID
  
## Jasper Custom Reports

* PD
  - [x] Report profile is created.
  - [x] Stored procedure is inserted.
  - [x] Dashboard uploaded to JasperServer
  - [ ] Dashboard has correct resource ID
  
* TR
  - [x] Report profile is created.
  - [x] Stored procedure is inserted.
  - [x] Dashboard uploaded to JasperServer
  - [ ] Dashboard has correct resource ID

* CV
  - [x] Report profile is created.
  - [x] Stored procedure is inserted.
  - [x] Dashboard uploaded to JasperServer
  - [ ] Dashboard has correct resource ID
