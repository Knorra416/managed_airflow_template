# CodeBuild Tempaltes
This section covers generic codebuild template scripts to interact with your Airflow Managed Environment. These utilities will connect to a designated Github Repository and drop files on S3, the locations Airflow will read to pull DAGs and utility scripts.


## CodeBuild Files

1. buildspec.yml
   - This is a file which specifies the commands you want to run when the codebuild project is triggered. In our case, we want to copy two locations: DAGs and scripts to places on S3 where Airflow will read.
2. codebuild_deployment_template.yml
   - This CFN template creates a codebuild project and role to trigger on push or pull requests merged to a branch named "main"
