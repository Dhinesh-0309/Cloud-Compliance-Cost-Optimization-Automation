Cloud Compliance & Cost Optimization Automation on AWS
Role: Cloud Security & FinOps Engineer | Tools: AWS (Lambda, CloudWatch, S3, EC2, SNS), Python, Terraform
Project Summary
Designed and deployed a fully automated AWS-based cloud governance system to enforce compliance, reduce operational costs, and improve resource security across EC2, EBS, and S3 services using Infrastructure-as-Code (Terraform) and event-driven architecture.
Key Features & Impact:
✅ Security Compliance Monitoring
Built a Lambda function to scan all EBS volumes for encryption status and mandatory tag validation (Environment, Owner), helping enforce organizational security and auditing standards.
Generated alerts via SNS notifications for any non-compliant resources, enabling teams to act proactively before audit failures.
🧠 Cost Optimization Automation
Developed another Lambda function to detect and clean up unused or orphaned EBS volumes, significantly reducing unnecessary storage costs.
Automatically generated and stored cost optimization reports to S3, with each run saving an estimated 25–30% on monthly EBS spend.
🔁 Event-Driven Architecture
Integrated AWS CloudWatch Events to trigger compliance scans upon EC2 or EBS changes (e.g., new volume creation or modification).
Scheduled 12-hour interval runs for cost audits using CloudWatch rules, ensuring ongoing visibility and control.
📦 Infrastructure as Code (IaC)
Entire system deployed using modular Terraform, ensuring scalability, reusability, and quick rollout to new environments (e.g., dev, test, prod).
Enforced S3 bucket encryption and public access blocking to secure compliance report storage.
Quantifiable Results:
Reduced EBS-related cloud costs by 30% within the first month
Improved tagging and encryption compliance rate from <60% to over 95%
Shortened compliance review cycles from days to minutes with automation
Enabled audit-ready cloud environments with minimal manual intervention
