https://developer.hashicorp.com/terraform/tutorials/aws-get-started/infrastructure-as-code


First, install the HashiCorp tap, a repository of all our Homebrew packages.

$ brew tap hashicorp/tap

Now, install Terraform with hashicorp/tap/terraform.

$ brew install hashicorp/tap/terraform


Initialize
Create main.tf files to describe resources
$ touch main.tf

Run terraform init to initialize the working directory and download necessary plugins for providers.

$ terraform init

Run  to view what changes Terraform will apply.
$ terraform plan

to execute the configuration and provision resources.
$ terraform apply

Run terraform destroy to tear down all managed infrastructure.
$ terraform destroy

