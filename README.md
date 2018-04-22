# cloudformation-templates
A collection of AWS CloudFormation templates


Before running the `aws-cloudformation-elasticsearch-service.yaml` template, you need to setup a service-linked iam role via the cli as this isnt supported with CloudFormation yet:
```bash
aws iam create-service-linked-role --aws-service-name es.amazonaws.com
```
