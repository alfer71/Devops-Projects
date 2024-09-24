## Project 3:
### Complete CI/CD with Terraform.

**Technologies used:**
*Terraform, Jenkins, Docker, AWS, Git, Java, Maven, Linux, Docker Hub*

---

**Project Description:**
Integrate provisioning stage into complete CI/CD Pipeline to automate provisioning server instead of deploying to an existing server.

- Create SSH Key Pair
- Install Terraform inside Jenkins container
- Add Terraform configuration to application’s git repository
- Adjust Jenkinsfile to add "provision" step to the CI/CD pipeline that provisions EC2 instance
- So the complete CI/CD project we build has the following configuration:
    - a. CI step: Build artifact for Java Maven application
    - b. CI step: Build and push Docker image to Docker Hub
    - c. CD step: Automatically provision EC2 instance using TF
    - d. CD step: Deploy new application version on the provisioned EC2 instance with Docker Compose

---

*Infrastructure as Code with Terraform*
