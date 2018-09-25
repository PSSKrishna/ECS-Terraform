# Terraform Module to create an Amazon Web Services (AWS) EC2 Container Service (ECS) cluster.



## Variables
Following is the list of default variables used to launch the ECS Cluster
```
vpc_id = (vpc_id) 
ami_id = (ami-6944c513)
ami_owners = [ self ,  amazon ,  aws-marketplace ]
lookup_latest_ami = (false)
root_block_device_type = (gp2)
root_block_device_size = (8)
instance_type = (t2.micro)
key_name = (key_name)
cloud_config_content_type = (text/cloud-config) 
health_check_grace_period = (600)
desired_capacity = (1) 
min_size = (1) 
max_size = (1) 
scale_up_cooldown_seconds =  300 
scale_down_cooldown_seconds =  300 
high_cpu_evaluation_periods =  2 
high_cpu_period_seconds =  300 
high_cpu_threshold_percent =  90 
low_cpu_evaluation_periods =  2 
low_cpu_period_seconds =  300 
low_cpu_threshold_percent =  10 
high_memory_evaluation_periods =  2 
high_memory_period_seconds =  300 
high_memory_threshold_percent =  90 

```


## Outputs

- `id` - The container service cluster ID
- `name` - The container service cluster name
- `container_instance_security_group_id` - Security group ID of the EC2 container instances
- `container_instance_ecs_for_ec2_service_role_name` - Name of IAM role associated with EC2 container instances
- `ecs_service_role_name` - Name of IAM role for use with ECS services
- `ecs_service_role_arn` - ARN of IAM role for use with ECS services
- `container_instance_ecs_for_ec2_service_role_arn` - ARN of IAM role associated with EC2 container instances
- `container_instance_autoscaling_group_name` - Name of container instance Autoscaling Group
