#1 Create a python file containing the code that needs to be run in lambda and store it in the same directory as your terraform 

#2 create the archive data block which will convert your python code in .zip format 

#3 create IAM policy for the iam role with all the permission required for the lambda excecution 

#4 create a IAM role and attach the policy on it 

#5 create a Lambda function with the same file path as your python ZIP code 

#6 RUN  terraform init to initialize the provider 

#7 RUN  terraform apply to execute your terraform code 

#8 go to aws console and then in lamda function you will be able to see the lamda function created in terraform. make a test and run the code to see the desired output
