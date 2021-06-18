# Usage

aws cloudformation create-stack --stack-name Fitnesse --template-body file://main.yaml --parameters ParameterKey=HostedZoneId,ParameterValue=<YOUR_ID> ParameterKey=AzureTenantId,ParameterValue=<YOUR_ID> ParameterKey=ClientId,ParameterValue=<YOUR_ID> ParameterKey=ClientSecret,ParameterValue=<YOUR_SECRET> ParameterKey=Owner,ParameterValue=<YOUR_NAME> --capabilities CAPABILITY_IAM
