# django-aws-cloudformation

AWS CloudFormation template file to create a stack that consists of EC2 instance(s) that hosts your application and the RDS Aurora database. 

In addition, this template also supports:
* EC2 Auto Scaling Groups which adds High Availability to your application
* application deployment using AWS CodeDeploy by including the installation of codedeploy agent
* Elastic IP creation, so your stack is DNS ready.
* ability to store the CloudFormation logs into AWS Cloudwatch, for easier troubleshooting
