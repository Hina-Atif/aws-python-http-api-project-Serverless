# aws-python-http-api-project
AWS Python HTTP API Project using Serverless Framework for scalable, cloud-native serverless applications

**Owner:** Hina Atif

## Project Description
This project demonstrates a Serverless Python HTTP API deployed on AWS using AWS Lambda and API Gateway.  
It provides a lightweight, scalable, and cost-efficient backend solution for handling HTTP requests without requiring server management.  

**Key Benefits:**
- Serverless architecture reduces infrastructure management overhead
- Cost-efficient: pay only for actual usage
- Highly scalable and reliable
- Easy to deploy and maintain
- Built-in monitoring via AWS CloudWatch

  
## 🖼️ Project Gallery

### 🏗️ Development & Deployment
Documentation of the project lifecycle from CLI initialization to successful cloud deployment.


![WhatsApp Image 2025-12-22 at 8 27 36 PM](https://github.com/user-attachments/assets/c3024af5-8aa7-4727-827d-d789500380e8)
![09-web-response2](https://github.com/user-attachments/assets/7cf7650b-af5b-40ff-9a11-7b9113ad5c3f)
![08-web-response](https://github.com/user-attachments/assets/d4e2607a-9f82-46e4-9da4-ac2355959ead)
![07-api-gateway-trigger png](https://github.com/user-attachments/assets/b92bf11f-df5e-46cb-bbf3-cbadfb5d650f)
![06-cloudwatch-logs png](https://github.com/user-attachments/assets/2bb8fc57-aaa6-4d18-8a63-aa6b729a3836)
![05-cloudformation-stack png](https://github.com/user-attachments/assets/6e252d4d-fb5b-4352-b3c8-afa9c8bc8d71)
![04-aws-lambda-list png](https://github.com/user-attachments/assets/ee27f764-4345-46bd-8a18-17c7a2514b9e)
![03-deploy-success png](https://github.com/user-attachments/assets/b0712c4f-036c-4a79-9f95-2a9f3d960351)
![02-python-logic](https://github.com/user-attachments/assets/7a13cabc-5707-4448-87a4-7c552442a26a)
![01-project-init](https://github.com/user-attachments/assets/223e7457-3d59-4060-8572-eeb55133f725)

## Tech Stack & Tools
- **Programming Language:** Python 3.12
- **Serverless Framework:** Deployment configuration and automation
- **AWS Lambda:** Serverless compute
- **AWS API Gateway (HTTP API):** Routing and HTTP endpoint management
- **AWS CloudFormation:** Managed deployment stacks
- **AWS CloudWatch:** Logs and monitoring of Lambda functions
- **Git & GitHub:** Version control and project hosting

---

## Project Structure

aws-python-http-api-project/
├── handler.py # Lambda function logic
├── serverless.yml # Serverless Framework configuration
├── unzip_requirements.py # Script for packaging dependencies
├── README.md # Project documentation

---

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/Hina-Atif/aws-python-http-api-project.git

Deploy the API using Serverless Framework (if desired):

sls deploy (serverless deploy)

You can access the API endpoints as deployed on AWS (check Serverless output for URLs).

🚀 Deployment Screenshots

| CloudFormation Stack                                             | Lambda Functions                                        |
| ---------------------------------------------------------------- | ------------------------------------------------------- |
| ![CloudFormation Stack](screenshots/05-cloudformation-stack.png) | ![Lambda Functions](screenshots/04-aws-lambda-list.png) |



API Gateway & Monitoring
| API Triggers                                           | CloudWatch Logs                                        |
| ------------------------------------------------------ | ------------------------------------------------------ |
| ![API Gateway](screenshots/07-api-gateway-trigger.png) | ![CloudWatch Logs](screenshots/06-cloudwatch-logs.png) |




Live API Verification
| Desktop Output                                    | Mobile Output                                      |
| ------------------------------------------------- | -------------------------------------------------- |
| ![Desktop Test](screenshots/08-web-response.jpeg) | ![Mobile Test](screenshots/09-mobile-response.png) |






