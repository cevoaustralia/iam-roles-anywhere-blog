# iam-roles-anywhere-blog

This repository is created to accompany the IAM Roles Anywhere Blog post.

It contains:

* CloudFormation Template to create a set of IAM Roles Anywhere resources required to begin and permission to assume the CDK roles
* The CDK Bootstrap template (current at the time of writing) modified with the `sts:TagSession` and `sts:SetSourceIdentity` applied to the relevant CDK IAM roles
