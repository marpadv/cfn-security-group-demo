# cfn-security-group-demo

CloudFormation template to create an AWS Security Group.

## Usage

```bash
aws cloudformation deploy \
  --template-file template.yaml \
  --stack-name my-security-group \
  --parameter-overrides VpcId=vpc-xxxxxxxx
```
