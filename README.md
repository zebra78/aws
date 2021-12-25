# aws
aws cloud
To run cloudformation template with parameters file, i was only able to do using parameters json only but not yaml file
The cloudformation template should be self executable the override values are supplied in the parameters json file.
E.g.:
ubuntu@awscli:~/GitHub/aws$ aws cloudformation create-stack --stack-name create-vpc --template-body file://create-vpc-cfn.yaml --parameters file://create-vpc-params.json