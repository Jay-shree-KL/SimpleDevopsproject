Project Name
Automated Flask Application Deployment

Technologies:
- Python
- Flask
- Git
- GitHub
- Docker

Architecture:
Developer → GitHub → Docker → Container → Application

How to run:
docker build -t devops-app:v1 .
docker run -d -p 5000:5000 devops-app:v1