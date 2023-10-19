# aws-cli-k8s



####terraform workspace
terraform workspaces are specific to directories.
Terraform workspaces are tied to specific directories. If you're in a different directory, you won't see the workspaces created in other locations.
#### getting current aws profile:
aws sts get-caller-identity

export AWS_PROFILE=tb-stage
