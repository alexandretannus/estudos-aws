# AWS Cost Management

## Elastic Cloud Computing (EC2)
- Billing time frame in seconds (some Linux instances) or minutes
### Charged
- Compute uptime of the instance based on the family and type
- Amount of data provisioned
- Detailed monitoring
### Free
- Basic Monitoring
- Amazon Machine Images (AMI)
- Private IP address

## Elastic Block Store (EBS)
### Charged
- Amount of data provisioned 
- Provisioned IOPS
- Storage consumed by snapshots
### Free
- Amount of data consumed  (inbound data transfer)
- Private IP address

## Relational Database Storage

### Charged
- Type and size of database
- Uptime
- Additional backup storage
- Outbound data transfer
- Multi AZ
### Free
- Amount of data consumed  (inbound data transfer)
- Single AZ
- Backup up to DB size

## AWS Organization
- Lower overall monthly expenses
  - Pool usage across multiple accounts (pricing tier discount)
- *Master* account pays charges for all *client* accounts
### Consolidated billing for multiple accounts
- One bill 
- Track charges 
- Combine charges (volume pricing discounts)
- No extra fee

## AWS Budgets
- Create threshold-based alerts
- Avalilable for EC2, RDS, Redshift, ElastiCache and Elasticsearch

## AWS Cloud Watch
- Monitor estimated AWS charges

## AWS Cost Explorer 
- Visualize and understand costs

## AWS Cost and Usage Report
- View usage for AWS services by category

## AWS CloudTrail
- Log API activity

## Total Cost of Ownership (TCO)
- Compare on-premises and AWS Cloud costs
- Document all the costs
  - Facilities equipment installation 
  - Facility operation
  - Data security
  - Hardware procurement teams
  - 