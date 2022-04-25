# aws-iam-policies

## Purpose
You manage access in AWS by creating policies and attaching them to IAM identities (users, groups of users, or roles) or AWS resources. A policy is an object in AWS that, when associated with an identity or resource, defines their permissions. AWS evaluates these policies when an IAM principal (user or role) makes a request. Permissions in the policies determine whether the request is allowed or denied. Most policies are stored in AWS as JSON documents. AWS supports six types of policies: identity-based policies, resource-based policies, permissions boundaries, Organizations SCPs, ACLs, and session policies.

IAM policies define permissions for an action regardless of the method that you use to perform the operation. For example, if a policy allows the GetUser action, then a user with that policy can get user information from the AWS Management Console, the AWS CLI, or the AWS API. When you create an IAM user, you can choose to allow console or programmatic access. If console access is allowed, the IAM user can sign into the console using a user name and password. Or if programmatic access is allowed, the user can use access keys to work with the CLI or API.

AWS uses policies to explicitly manage resources access, using one of the following permissions:

- "allow"
- "deny"
- "not action"

The policies within this repository are closely matched between the AWS GovCloud and Commercial accounts. The policies will be noted as being in GovCloud or Commercial.
