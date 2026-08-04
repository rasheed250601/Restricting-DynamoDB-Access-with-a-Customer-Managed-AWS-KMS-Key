# Restricting-DynamoDB-Access-with-a-Customer-Managed-AWS-KMS-Key
Encrypted a DynamoDB table with a customer-managed KMS key scoped to one IAM user via key policy. Verified enforcement by testing with a second IAM user holding full DynamoDB access but no key permissions — request was denied at the KMS layer, proving encryption as a real access-control boundary.
