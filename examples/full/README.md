# Full example

Creates an ECS cluster backed by an autoscaling EC2 cluster with EFS mounting enabled.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| public\_key | The public key for the SSH key needed to SSH to the EC2 instances in the ECS cluster | string | `"ssh-rsa AAAAB3NzaC1yc2EAAAABJQAAACEApggnkvLGHyI5/k8auZl4BuIgWFXmVanCUu9hD0wr35c= dummy-key"` | no |
| region | The AWS region to deploy in | string | `"eu-west-1"` | no |

