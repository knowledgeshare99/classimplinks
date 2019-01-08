# class important links
This is class screening important links

#Tomcat server links
https://tomcat.apache.org/tomcat-7.0-doc/appdev/sample/



# ======== AWS cloud compute links =========

# Cloud trial

https://blog.powerupcloud.com/capture-ec2-launch-termination-events-using-cloudtrail-cloudwatch-lambda-570461d9942a

# NAT Gateway

# S3 service 

#How to make S3 bucket as a mount device

https://github.com/knowledgeshare99/s3fs-fuse-rs

https://cloudkul.com/blog/mounting-s3-bucket-linux-ec2-instance/

#How to restrice the bucket from public internet to access only from specific CIDR range
https://docs.aws.amazon.com/AmazonS3/latest/dev/example-bucket-policies.html


# AWS Secrets Manager

https://aws.amazon.com/compliance/services-in-scope/
#How does AWS Secrets Manager encrypt my secrets?
AWS Secrets Manager uses envelope encryption (AES-256 encryption algorithm) to encrypt your secrets in AWS Key Management Service (KMS).When you first use Secrets Manager, you can specify the Customer Master Keys (CMKs) to encrypt secrets. If you do not provide a CMK, Secrets Manager creates AWS KMS default keys for your account automatically. When a secret is stored, Secrets Manager requests a plaintext and an encrypted data key from KMS. Secrets Manager uses the plaintext data key to encrypt the secret in memory. AWS Secrets Manager stores and maintains the encrypted secret and encrypted data key. When a secret is retrieved, Secrets Manager decrypts the data key (using the AWS KMS default keys) and uses the plaintext data key to decrypt the secret. The data key is stored encrypted and is never written to disk in plaintext. Also, Secrets Manager does not write or cache the plaintext secret to persistent storage.

# Route 53 services
https://www.bogotobogo.com/DevOps/AWS/aws-Route53-DNS-Private-Hosted-Zone.php

# Amazon API Gateway
https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html

#IP Whitelisting with Amazon API Gateway

https://lobster1234.github.io/2018/04/14/amazon-api-gateway-ip-whitelisting/


# Lambda functions URLs

#VPC - Notify On Invalid External Peering Connections

https://www.capitalone.io/docs/usecases/vpcpeeringcrossaccount.html


#RDS - Terminate Unencrypted Public Instances

https://www.capitalone.io/docs/usecases/rdspublicunencrypted.html

#RDS - Delete Unused Databases With No Connections

https://www.capitalone.io/docs/usecases/rdsdeleteunused.html

#Lambda Function to maintain s3 lifecycle managment

https://github.com/aws-samples/aws-lambda-lifecycle-hooks-function/blob/master/lambda_backup.py

# Cloud formation links:

https://github.com/stelligent/application-loadbalancer-multi-cert

https://aws.amazon.com/premiumsupport/knowledge-center/nat-gateway-vpc-private-subnet/

https://aws.amazon.com/blogs/aws/new-managed-nat-network-address-translation-gateway-for-aws/

http://www.tothenew.com/blog/launching-an-aws-ec2-instance-using-cloudformation-template/

#Best examle for existing infra services to use

https://github.com/awslabs/aws-cloudformation-templates/blob/master/community/services/VPC/vpc_template.json
https://github.com/stelligent/cloudformation_templates/blob/master/infrastructure/vpn-static.json

#Most helpful cfn templates for building all EC2-ASG-ELB-CWAlarms-Route53
https://github.com/cloudtools/troposphere/pull/656/commits/b957ef56bce501c9525532951e06eced0a074946#diff-900790531ed2821872b805a3a4cdfbf5

https://gist.github.com/donavanm/2156480

#AWS Cognito Cloudformation
https://gist.github.com/singledigit/2c4d7232fa96d9e98a3de89cf6ebe7a5

#Uploading a Server Certificate into both IAM and ACM (also update into Cloudfront)
https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_server-certs.html

https://aws.amazon.com/premiumsupport/knowledge-center/import-ssl-certificate-to-iam/

https://aws.amazon.com/premiumsupport/knowledge-center/custom-ssl-certificate-cloudfront/

#A New and Standardized Way to Manage Credentials in the AWS SDKs
#How to create a AWS profile in your local aws credential store

https://aws.amazon.com/blogs/security/a-new-and-standardized-way-to-manage-credentials-in-the-aws-sdks/

# =====================================================

#                   DevOps

# =====================================================



#Git and GitHub

https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell

# ============= Jenkins ==========

#Deploy static web page from GitLab to Amazon S3 using Jenkins

https://www.codeproject.com/Articles/1222632/%2FArticles%2F1222632%2FDeploy-static-web-page-from-GitLab-to-Amazon-S-usi


# ======== Ansible Configuration Management  ========

#Anisble playbooks automation :
#Ansible Playbooks and Ansible Vaults with Examples

https://www.softwaretestinghelp.com/ansible-playbooks-ansible-vaults/

#Ansible Galaxy and Galaxy Community

https://docs.ansible.com/ansible/2.4/galaxy.html

https://galaxy.ansible.com/community

#Ansible Roles Explained with examples

https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html

https://www.learnitguide.net/2018/02/ansible-roles-explained-with-examples.html

#Ansible Roles: Making your Playbooks reusable

http://redhatgov.io/workshops/ansible_tower/exercise1.5/

# ====== KONG API Gateway vs AWS API Gateway ========

Installation steps on #CentOS7

https://github.com/knowledgeshare99/kong.git

https://docs.konghq.com/install/centos/#packages

https://github.com/knowledgeshare99/kong.git

#Using docker-file 

https://github.com/docker-library/docs/tree/master/kong

#Using CloudFormation template

https://docs.konghq.com/install/aws-cloudformation/

Configuration loading Kong

https://docs.konghq.com/0.11.x/configuration/

#kong Auto start/stop/health etc,..

https://github.com/Kong/kong/issues/2471

# ====== Service Discovery (consul) clouster setup =======

#Important links

https://gist.github.com/sdorsett/5cf05bb5e02f1e4a20224bae62b375ea

http://www.adambonny.com/installing-consul-server-on-centos/

https://linuxthegreat.wordpress.com/2017/09/19/hashicorp-consul-installation-on-centos-7/

https://www.digitalocean.com/community/tutorials/how-to-configure-consul-in-a-production-environment-on-ubuntu-14-04

https://www.consul.io/docs/agent/options.html

https://www.consul.io/intro/getting-started/install.html

https://www.consul.io/docs/agent/options.html

#SD via Consul with ECS AWS

https://aws.amazon.com/blogs/compute/service-discovery-via-consul-with-amazon-ecs/

https://medium.com/@opsline/consul-service-discovery-for-ecs-87b845445d7b

https://medium.com/containers-on-aws/how-to-setup-service-discovery-in-elastic-container-service-3d18479959e6

#SD via consul with ECS AWS - Github CFN

https://github.com/awslabs/service-discovery-ecs-consul/blob/master/service-discovery-blog-template

# ====== Issuses fix links ========
 Nice :
 
https://devopscube.com/setup-consul-cluster-guide/

#Issue faced :consul remote state is encrypted and encryption is not configured

Solutin fixed:

https://github.com/hashicorp/consul/issues/719

# ======= DB Related ========
# PostgreSql installation on Ubunto

https://www.godaddy.com/garage/how-to-install-postgresql-on-ubuntu-14-04/

#postgresql failover
https://aws.amazon.com/blogs/database/failover-with-amazon-aurora-postgresql/

# DynamoDB

https://aws.amazon.com/blogs/database/how-to-use-aws-cloudformation-to-configure-auto-scaling-for-amazon-dynamodb-tables-and-indexes/

https://github.com/widdix/aws-cf-templates/blob/master/state/dynamodb.yaml


