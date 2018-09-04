# Terraform Module to create an Amazon Web Services (AWS) EC2 Container Service (ECS) cluster.

## Outputs

- `id` - The container service cluster ID
- `name` - The container service cluster name
- `container_instance_security_group_id` - Security group ID of the EC2 container instances
- `container_instance_ecs_for_ec2_service_role_name` - Name of IAM role associated with EC2 container instances
- `ecs_service_role_name` - Name of IAM role for use with ECS services
- `ecs_service_role_arn` - ARN of IAM role for use with ECS services
- `container_instance_ecs_for_ec2_service_role_arn` - ARN of IAM role associated with EC2 container instances
- `container_instance_autoscaling_group_name` - Name of container instance Autoscaling Group
