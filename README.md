# managed_airflow_template
CFN templates for easy start Managed Airflow in AWS

Prerequesist:

1. You need a role for the AWS environment. Pleasse see the AWS docs here: https://docs.aws.amazon.com/mwaa/latest/userguide/mwaa-create-role.html
2. You need a VPC where the Airflow environment will be located. Please see the AWS docs here: https://docs.aws.amazon.com/mwaa/latest/userguide/vpc-create.html
3. Custom plugins can be added in this format: https://docs.aws.amazon.com/mwaa/latest/userguide/configuring-dag-import-plugins.html


Access the Web UI:
- See AWS docs here for accessing the web UI once your environment is setup: https://docs.aws.amazon.com/mwaa/latest/userguide/access-airflow-ui.html