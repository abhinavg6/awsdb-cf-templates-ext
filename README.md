# awsdb-cf-templates-ext
Specific / Nuanced Cloudformation Templates for AWS Databricks E2 Workspace Provisioning

Following types of templates are available here:
* BYO VPC Resources - To create required networking infrastructure in customer's own managed VPC
* Cross-Account IAM Role - To create the cross-account IAM role for Databricks account to provision compute resources
* DBFS Root S3 Bucket - To create the root S3 bucket and apply bucket policy to allow Databricks account to access it

*Note:* E2 or Enterprise 2.0 is a preview feature that is available only after Databricks has qualified / validated the requirements. It needs Databricks to whitelist and create a new master account for all such workspaces. Please reach out to your Databricks account team for access to the preview.
