DevOps technical exam:  
Part 1:  
1. Create a Github repository named "Crescendo-DevOps-exam"  
2. Create an AWS infrastructure template using terraform.(VPC, EC2, ALB, Cloudfront)  
a.  The terraform should also automatically install Nginx, and Tomcat upon provisioning of  
EC2. (Automating part 2 of the exam via terraform is a huge plus)  
b. The terraform template should have 2 private subnets and 2 public subnets.  
c. The terraform template should have a 1 NAT gateway and 1 Internet gateway.  
3. Create a github action that will plan/apply the terraform to an AWS account (No need to 
run the services, a successful return in terraform plan is enough).  
4. Create a github action that will destroy the services in the AWS account.  
5.Share the repository to “bobcres / R3ymark” github username.  
Plus points: 
A. If you create an RDS PostgreSQL free tier instance that can communicate to the EC2 
and it can only be access via Private Endpoint. 
B. If you setup a monitoring tool to your local/wsl/vm/docker but could aggregate logs 
from the EC2 or local where you ran your terraform template. 
Part 2:  
1. Setup a simple Magnolia CMS application in either your local VM or EC2 instance(see 
here  
for instructions.)  
2. Proxy the running magnolia instance to port 80 via nginx.(Bonus if you can get it running 
in  
443 using a self-signed certificate.) 
