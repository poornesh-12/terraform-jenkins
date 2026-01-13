# terraform-jenkins

This project creates **two files** and **two directories** using Terraform via a Jenkins.

---

## Structure

- `main.tf` – Terraform code to create files and directories using the `local_file` resource  
- `Jenkinsfile` – CI pipeline to run Terraform stages (`init`, `validate`, `plan`, `apply`)

---

## How to Use

1. Connect this repository to Jenkins (Pipeline script from SCM)
2. Run the Jenkins pipeline
3. Check the Jenkins workspace – it will contain:

