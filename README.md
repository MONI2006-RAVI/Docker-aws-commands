This repository contains Docker and AWS configuration files to containerize and deploy an application efficiently. It is designed for students and beginners to gain hands-on experience with Docker, Docker Compose, and AWS cloud deployment.

📁 Project Contents

docker-compose.yaml – Defines and manages multi-container services.

docker commands_aws_config.txt – Contains essential Docker and AWS CLI commands.

Screenshots – Show successful container execution and Docker Desktop interface.

🛠️ Prerequisites

Docker Desktop installed

AWS account (for cloud deployment)

Basic knowledge of command line

▶️ How to Run the Project

Clone the repository:

git clone <your-repo-url>
cd Moni


Start the containers:

docker compose up --build


or

docker-compose up --build


Open Docker Desktop to monitor running containers.

Access the application using the port mentioned in docker-compose.yaml (e.g., http://localhost:8080).

☁️ AWS Deployment

Use the commands provided in docker commands_aws_config.txt to:

Configure AWS credentials

Create repositories in AWS ECR

Push Docker images to AWS

🎯 Learning Outcomes

Understand Docker containerization

Manage multi-container apps with Docker Compose

Deploy applications to AWS

Monitor containers using Docker Desktop
