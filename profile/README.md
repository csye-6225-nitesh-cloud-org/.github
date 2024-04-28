## Hi there 👋
## Welcome to my GitHub organization dedicated to cloud computing! Below you will find information about each repository within my organization.

## Repositories

### 1. [tf-gcp-infra](https://github.com/csye-6225-nitesh-cloud-org/tf-gcp-infra)

This repository contains Infrastructure as Code (IaC) using Terraform for managing Google Cloud Platform (GCP) infrastructure. It includes configurations for provisioning various resources such as VPC, subents, firewall, Cloud SQL, storage buckets, Autoscaler, LoadBalancer, MIG and more.

### 2. [webapp](https://github.com/csye-6225-nitesh-cloud-org/webapp)

The webapp repository houses the API for user management, which has been deployed on Google Cloud Platform. Here's what you can find in this repository:
  
The "webapp" repository implements comprehensive CI/CD pipelines using GitHub Actions. These pipelines include integration tests to ensure code quality and reliability. Additionally, the repository integrates Packer for custom image creation, guaranteeing consistent and reproducible deployments.

Moreover, the CI/CD process automatically generates new images for each new version of the application. Subsequently, it seamlessly initiates rolling updates by creating new instance templates for the Managed Instance Group (MIG), which is intricately connected with a load balancer for efficient traffic distribution.

### 3. [Serverless](https://github.com/csye-6225-nitesh-cloud-org/serverless)

The Serverless repository contains cloud function code designed to be triggered by Pub/Sub to send verification emails to users and track email interactions. This repository integrates with the webapp repository, where messages are published, initiating the workflow.

## How to Contribute

We welcome contributions from the community! Whether it's bug fixes, feature enhancements, or new ideas, feel free to submit pull requests and issues to any of our repositories.

To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Create a new Pull Request.

## Code of Conduct

Please note that we have a Code of Conduct that we expect all contributors and community members to adhere to. This ensures a welcoming and inclusive environment for everyone involved.

## License

All repositories within our organization are licensed under the [MIT License](LICENSE), unless otherwise specified in the repository. Please review the license file for more details.

