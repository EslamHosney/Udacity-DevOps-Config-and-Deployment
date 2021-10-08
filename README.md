# Udacity-DevOps-Config-and-Deployment
Create Infra using EC2 Cloud Formation then using Ansible configure the EC2
    -   1st add the Env Vars for AWS Authetication in Circle CI
            AWS_ACCESS_KEY_ID	xxxxIYUU
            AWS_DEFAULT_REGION	us-east-1 
            AWS_SECRET_ACCESS_KEY xxxxWx1p
    -   Add the template.yml to your commit to be accesable by the job to create teh EC2
    -   Add the public IP of EC2 to inventory file to be used by Ansible
    -   main-remote.yml is the main file for Ansible jobs to be applied
    -   create the file ansible.cfg to overcome teh error "Are you sure you want to     continue connecting (yes/no)?"
    -   

