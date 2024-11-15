# Static-S3-Website-with-Terraform.

In this post, I walk through deploying a static S3 website on AWS using Terraform, assessing security with Prowler, and highlighting key takeaways.

Day 1 of #90 - Days of Cloud Security.

Today's lab focused on creating a static website hosted on AWS S3 using Terraform.

I’ve used Terraform before, so after configuring my AWS credentials, I quickly set up the infrastructure in VSCode.

Once deployed, I used Prowler to run a security check on my AWS account, and unsurprisingly, the S3 website had some security gaps.

Key Takeaways:

Infrastructure as Code (IaC) with Terraform automates setup, making it repeatable and versioned.

Prowler is an open-source security tool for AWS, Azure, Google Cloud, and Kubernetes to assess security, perform audits, and recommend fixes.

S3 bucket security is crucial: ensure public access is blocked, apply strict permissions, enable logging, and use encryption to safeguard sensitive data.

#CloudSecurity #AWS #S3 #Cybersecurity #Terraform #Prowler
