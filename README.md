# Node Todo CICD Project

This is a simple Node.js TODO application used to demonstrate CI/CD with Docker.

## 📌 Author
- **Name:** Vishal Yadav  
- **Email:** devops.vishal8227@gmail.com  
- **Phone:** +91-7841048227

## 🚀 Tech Stack
- Node.js
- Express.js
- Docker

## 🐳 Docker Commands
```bash
# Build the Docker image
docker build -t node_todo_app:v1 .

# Run the container
docker run -d --name node-app -p 8000:3000 node_todo_app:v1
# Node-Todo-CICD
