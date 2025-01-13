# Terraform AWS VPC Module Customised
# Inputs
* project_name (Mandatory): User must supply their project name.
* environment (Mandatory): User must supply their environment name.
* vpc_id (Mandatory): User must supply their VPC CIDR.
* sg_name (Mandatory): User must supply their security group  name
* common_tags (Optional): Default is empty. User can supply tags in map(string) format.
* sg_tags (Optional): Default is empty. User can supply tags in map(string) format.

# Outputs
* id : Security group id