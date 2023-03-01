# terraform-interview-ques
What is Terraform?
Answer: Terraform is an open-source infrastructure as code (IaC) tool developed by HashiCorp that enables users to define and provision infrastructure resources in a declarative language. It provides a consistent workflow to manage infrastructure resources across multiple cloud providers and on-premises environments.

What is Infrastructure as Code?
Answer: Infrastructure as Code (IaC) is a process of defining and provisioning infrastructure resources using code rather than manual processes. It allows for consistent, repeatable deployments, and enables version control and collaboration among team members.

What are the benefits of using Terraform?
Answer: Terraform offers many benefits, including:

Consistent and repeatable infrastructure deployments
Simplified infrastructure management across multiple cloud providers and on-premises environments
Version control and collaboration
Automates the provisioning and management of infrastructure resources
Enables Infrastructure as Code practices
Increases infrastructure visibility and auditability
What is a Terraform module?
Answer: A Terraform module is a reusable set of Terraform resources that can be used across multiple projects or environments. It allows for easy sharing and reuse of infrastructure code, and helps to maintain consistency across different deployments.

What is the difference between Terraform's "apply" and "plan" commands?
Answer: The "plan" command generates a plan for changes to the infrastructure, showing what resources will be created, modified, or deleted. The "apply" command then applies those changes to the actual infrastructure. Essentially, "plan" shows what changes will be made, while "apply" actually makes those changes.

What is the Terraform state file?
Answer: The Terraform state file is a JSON file that stores information about the infrastructure resources created and managed by Terraform. It includes information about the current state of the resources, such as their configuration and metadata. The state file is used by Terraform to manage changes to the infrastructure, and should be stored securely and backed up regularly.

How do you handle sensitive data in Terraform?
Answer: Sensitive data, such as passwords and API keys, should never be stored in plain text in Terraform configuration files. Instead, Terraform offers several methods for handling sensitive data, including environment variables, encrypted variables, and third-party secret management tools like HashiCorp Vault.

What is the difference between Terraform and other IaC tools like Ansible and Chef?
Answer: Terraform is focused specifically on managing infrastructure resources, while Ansible and Chef are more general-purpose automation tools. Terraform is designed to be cloud-agnostic and can manage resources across multiple cloud providers and on-premises environments, while Ansible and Chef are primarily focused on configuration management and automation on individual servers.





