README
Use the following code on your aws to run :
aws cloudformation create-stack --stack-name udagram2 --template-body file://final-project-starter.yml    --parameters file://server-parameters.json  --region=us-east-1 --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM"
