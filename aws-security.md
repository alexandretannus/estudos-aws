# AWS Security

## Shared Responsibility
- Customer Responsibility
  - Configure IAM password policy
  - Install operationg system patches on EC2 instances
- AWS Responsibility
  - Secure disposal of faulty disk drives
  - Implement data center access controls
  - Install patches on physical hardware devices

## Identity and Acess Management - IAM
- Control individual and group access to AWS resources
- Authentication and Authorization
- Global service
- Least privilege principal
- Enable multi factor authentication (MFA)
### Access Key
- Long-term credentials
  - IAM user
  - AWS account root user
- Programmatic requests to AWS CLI or AWS API
- Two parts:
  - Access key ID
  - Secret Access Key
- Good practice: Rotate access key regularly
### User
- Entity that represent a person or service.
- Can have
  - Access key 
  - Password for management console access
#### AWS Root User
- Perform specific management tasks
  - Change account name
  - Change AWS support plans
  - Billing
  - Close account

### Roles
- Set of permissions
- No credentials associated
### Groups
- Collection of users
- User can be at multiple groups
### Policies 
- Document that defines permission
- Can be applied to user, groups and roles
- Written in JSON
- Default: all permissions denied
- AWS Policy Generator
  - Tool to create policies
### Access Advisor
- Feature to identify unnecessary user permission
- Accessible from IAM console

## Amazon Macie
- Data security and data privacy service
- Discover and protect sensitive data
- Automatic S3 buckets' inventory

## Amazon Cognito
- Web and mobile app authentication
- Supports social media (Facebook, Google) and enterprise sign-in

## AWS Security Token Service (STS)
- Web service for temporary and limited-privilege credentials

## AWS Shield
- Managed DDoS protection service

## AWS CloudHSM
- Encryption keys storage
- Higly secure

## Web Application Firewall (WAF)
- Protect web apps from common web exploits
- Protect on-premises resources if they are behind an Application Load Balancer (ALB)

## Amazon Guard Duty
- Threat detection service
- Monitor malicious activity and unauthorized behavior

## Amazon Detective
- Process event data records
  - IP traffic
  - AWS management operations
  - Malicious or unauthorized activity

## AWS Artifact
- AWS security and compliance documents
  - Service Organization Control (SOC)
  - Payment Card Industry (PCI)
  - Certifications from accreditation bodies

## Penetration tests
- Can be done without prior approval for: 
  - Amazon EC2 instances, NAT Gateways, and Elastic Load Balancers.
  - Amazon RDS.
  - Amazon CloudFront.
  - Amazon Aurora.
  - Amazon API Gateways.
  - AWS Lambda and Lambda Edge functions.
  - Amazon LightSail resources.
  - Amazon Elastic Beanstalk environments. 