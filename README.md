# RDS Example in AWS CDK - Complete Guide

A repository for an article on
[bobbyhadz.com](https://bobbyhadz.com/blog/aws-cdk-rds-example) `<- Update Link`

## How to Use

1. Clone the repository

2. Install the dependencies

```bash
npm install
```

3. Create a Key pair with the name of `ec2-key-pair` in your default region

4. Create the CDK stack

```bash
npx cdk deploy
```

4. Open the AWS CloudFormation Console and the stack should be created in your
   default region

5. Cleanup

```bash
npx cdk destroy
```
