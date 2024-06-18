# VPC, subnet, API Gateway, Lambda & DynamoDB

- [`src`](./src/) - Code for the application's Lambda function.
- [`cfn-template.yaml`](./cfn-template.yaml) - A template that defines the application's AWS resources.
- [`deployment-file.yaml`](./deployment-file.yaml) - Contains deployment info.
- [`pull-request.yaml`](./deployment-file.yaml) - Contains deplyment job workflow.

The application uses several AWS resources, including [AWS Lambda Functions](https://aws.amazon.com/lambda/), an [Amazon API Gateway REST API](https://aws.amazon.com/api-gateway/), and an [Amazon DynamoDB Table](https://aws.amazon.com/dynamodb/). These resources are defined in the [`cfn-template.yaml`](./cfn-template.yaml) file in this project. You can use the [SAM CLI](https://aws.amazon.com/serverless/sam/) to deploy and iterate on the Lambda function code and use AWS Application Composer to view and extend this application's architecture.
