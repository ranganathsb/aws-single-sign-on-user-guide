# Limits in AWS SSO<a name="limits"></a>

The following tables describe limits within AWS SSO\. For information about limits that can be changed, see [AWS Service Limits](http://docs.aws.amazon.com/general/latest/gr/aws_service_limits.html)\.

## Application Limits<a name="applicationlimits"></a>


| Resource | Default Limit | 
| --- | --- | 
|  File size of service provider SAML certificates \(in PEM format\)  | 2 kb | 
|  Number of unique Active Directory groups that can be assigned to an application \*  | 50 | 
|  Number of connected directories that you can have at a time  | 1 | 

\* Users within their Active Directory can belong to many directory groups\. However within AWS SSO, they can have up to 50 of their Active Directory groups assigned for using applications\.

## AWS Account Limits<a name="awsaccountlimits"></a>


| Resource | Default Limit | 
| --- | --- | 
| Maximum number of permission sets in AWS SSO | 50 | 
| Number of permission sets allowed per AWS account | 20 | 
|  Number of references to AWS managed policies per permission set  | 10 | 
| Number of inline policies per permission set | 1 | 
| Maximum size of inline policy per permission set | 10,000 bytes | 
|  Number of IAM roles in the AWS account that can be repaired at a time \*  | 1 | 

\* Permission sets are provisioned in an AWS account as IAM roles\. For more information, see [Permission Sets](permissionsetsconcept.md)\.

## AWS SSO Console Limits<a name="consolelimits"></a>


| Resource | Default Limit | 
| --- | --- | 
|  Maximum combined number of users and groups that you can assign access to an AWS account or cloud application at a time  | 5 | 