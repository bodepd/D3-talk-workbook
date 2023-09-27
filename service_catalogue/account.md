# Overview

The account service provisions accounts in AWS. These accounts are provisioned
together with the cloud foundations that both secure the account and allow
for the account to enable other shared services.

# Inputs

environment: the environment that the account is in, can be development, non-production, or production

business unit: the business unit that all resources in the account should be tagged as

account name: the name of the account

# Outputs

groups: The active directory groups that are created with the account, users assigned to these
groups can access the account based on the role of the group (admin or readonly)
