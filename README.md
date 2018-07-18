# aws-cicd-cloudformation
AWS Continuous Integration and Continuous Delivery Implementation using CloudFormation

Composed of 3 Stacks: (Needs to be created in this order)
1. IAM Layer
2. Components Layer (Underlying Components for CICD)
3. Application Layer 

IAM Layer: Roles && Policies + Initial Parameters (AppName, ProjectId, RepositoryName...)

![alt text](https://github.com/codeyasam/aws-cicd-cloudformation/blob/master/iam_layer.png)

Components Layer: CICD Components (CodeCommit, CodeBuild, CodeDeploy, CodePipeline...)

![alt text](https://github.com/codeyasam/aws-cicd-cloudformation/blob/master/components_layer.png)

Application Layer: EC2 Instance, SecurityGroup

![alt_text](https://github.com/codeyasam/aws-cicd-cloudformation/blob/master/application_layer.png)
