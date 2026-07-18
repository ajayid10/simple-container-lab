
📌 Project Overview
----------------------------------------

Simple Container Lab is a beginner-friendly Docker project that demonstrates how to containerize a basic Node.js application using Docker. The project is designed to introduce the fundamental concepts of containerization, image creation, and application deployment in a consistent and portable environment.

By packaging the application and its dependencies into a Docker image, the application can run reliably across different machines without requiring additional configuration.

--------------------------------------------------------------------------------------
**Project Objectives**

The primary objectives of this project are to:

Understand the fundamentals of Docker and containerization.
Learn how to create a Dockerfile.
Build a Docker image from a Node.js application.
Run an application inside a Docker container.
Gain hands-on experience with Docker commands and workflows.
Prepare a foundation for more advanced DevOps practices such as Docker Compose, Kubernetes, and CI/CD pipelines

-----------------------------------------------------------------------------




🛠️ Technologies Used
----------------------
Technology	       
Node.js 18       
Docker	         
Git	           
GitHub	       
Git Bash / vscode 

----------------------------------------------------



📁 Project Structure
ajayid10/
└── simple-container-lab/
    ├── Dockerfile
    ├── app.js
    └── README.md

-------------------------------------------------------------------








📄 Application Code

app.js

console.log("Hello, DevOps!");

----------------------------------------------------------





🐳 Dockerfile


------------------------------------------------------


FROM node:18-alpine

COPY app.js .

CMD ["node","app.js"









Build the Docker Image

docker build -t simple-container-lab:1.0 .

Run the Container
docker run --rm simple-container-lab:1.0

Expected output:

Hello, DevOps!

--------------------------------------------------





👨‍💻 Author

Ajayi Kolawole Daniel

GitHub: https://github.com/ajayid10
LinkedIn: https://www.linkedin.com/in/ajayikolawoledaniel

-----------------------------------------------------------------------------
