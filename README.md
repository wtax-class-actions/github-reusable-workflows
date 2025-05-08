# WTax GitHub Actions Workflows

This repository contains [reusable workflows for GitHub Actions](https://docs.github.com/en/actions/using-workflows/reusing-workflows).
As GitHub only allows reusable workflows to be in public repositories, this repository is public. Therefore, make sure 
not to commit any sensitive information to this repository: all sensitive information (i.e. passwords, keys, etc.) are 
to be passed in as secrets to the reusable workflow.

## Workflows

### For SFDX projects

| Name                                                                                | Description                                                                                                                           |
|-------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| [build-sfdx-project.yml](docs/build-sfdx-project.md)                                | Deploys source from a Salesforce DX project to a scratch org and runs tests                                                           |
| [deploy-sfdx-project.yml](docs/deploy-sfdx-project.md)                              | Deploys an SFDX project's metadata to an org                                                                                          |
| [deploy-sfdx-project-to-developer.yml](docs/deploy-sfdx-project-to-developer.md)    | Deploys an SFDX project's metadata to the developer sandbox                                                                      |
| [deploy-sfdx-project-to-uat.yml](docs/deploy-sfdx-project-to-uat.md)                | Deploys an SFDX project's metadata to the uat sandbox                                                                            |
| [deploy-sfdx-project-to-prod.yml](docs/deploy-sfdx-project-to-prod.md)              | Deploys an SFDX project's metadata to the production org                                                                         |
