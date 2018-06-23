# terraform-asg-elb
It will create AWS Asg and Launch configuration using Terraform 
What it will create is written below :-
1. Create a aws_launch_configuration
2. Create an AWS auto-scaling group
3. Create AWS autoscaling policy
4. Create AWS CloudWatch alarm 
5. Create a security group
6. Create an Elastic load balancer with cookie session persistence and use this load balancer in front of auto-scaling group
7. Create a SSH key pair and use for AWS auto-scaling group

