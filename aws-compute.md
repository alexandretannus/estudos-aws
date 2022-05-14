# AWS Compute

## Amazon EC2
- Full operating system instance
- Windows or Linux

### Types of Instances
#### On-Demand
- Pay for hours used with no commitment
- Applications with short term, spiky, or unpredictable workloads that cannot be interrupted
- No long term commitment
#### Dedicated 
- Isolated workloads
- Dedicated hardware for only one customer
- Useful for regulatory requirements that may not support multi-tenant virtualization. 
- Great for licensing which does not support multi-tenancy or cloud deployments
#### Reserved
- Pay for capacity ahead of time
- Applications with steady state or predictable usage or that require reserved capacity
- Commitment: 1 or 3 years
- Up to 75% discount
- Can not be redeemed
- Can be sold at AWS marketplace
#### Spot
- Applications that have flexible start and end times and that are only feasible at very low compute prices
- Spare computing capacity
- Very low price (bid controlled)
- Workloads can be terminated anytime
- Not reccomended for long term requirements

### Auto Scaling
- Stop guessing about capacity
- Adapt to the application's demand 
- Scale up and down as needed
- VPC across multiple availability zones (AZ)
- Can not launch resources into another region

## Storage 

### Elastic Block Store (EBS)
- Block storage service
- Used with EC2 instances
- Persisten storage

### Instance store volumes
- Block storage service
- Ephemeral storage

## Elastic Container Service (ECS)
- Run software containers

## Elastic Container Sevice for Kubernetes (EKS)
- Run software containers

## AWS Lambda
- Run code as functions
- No server provisioning or management
- Triggered by events

