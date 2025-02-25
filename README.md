# 🌍 Deploy A Website On AWS Using Terraform

A Terraform-based automation project that deploys a website on AWS with infrastructure-as-code principles.

## 🚀 Features
- Automates website deployment on AWS using Terraform.
- Creates and configures AWS resources such as:
  - **EC2 Instances**: Virtual servers to host the website.
  - **S3 Buckets**: For static website hosting or storing assets.
  - **Route 53**: Domain name system (DNS) management for routing traffic.
  - **Security Groups**: Firewall rules to control inbound/outbound traffic.
  - **Load Balancer**: Distributes traffic across multiple instances for high availability.
- Ensures infrastructure consistency and repeatability.

## 🛠️ Prerequisites
- [Terraform](https://www.terraform.io/downloads.html) installed on your system.
- An active AWS account with IAM credentials configured.
- Basic understanding of AWS services.

## 📦 Installation & Usage
### Clone the Repository
```bash
git clone https://github.com/Judewakim/DeployWebsiteOnAWSUsingTerraform.git
cd DeployWebsiteOnAWSUsingTerraform
```

### Initialize Terraform
```bash
terraform init
```

### Preview Infrastructure Changes
```bash
terraform plan
```

### Apply Changes to Deploy
```bash
terraform apply -auto-approve
```

### Destroy Infrastructure (Optional)
```bash
terraform destroy -auto-approve
```

## 📜 Example Output
```
Apply complete! Resources: 5 added, 0 changed, 0 destroyed.
Website deployed successfully at http://yourwebsite.com
```

## 📌 Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.

## 📜 License
This project is licensed under the MIT License.

---
🌟 *Happy Terraforming!*

