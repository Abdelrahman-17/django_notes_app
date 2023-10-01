# Simple Notes App
This is a simple notes app built with React and Django. 
 we will explore a DevOps project that involves deploying a Django notes app on an EC2 instance using Jenkins declarative CI/CD pipeline. 
 We will leverage Docker containers and Docker Hub for containerization and image management. The project focuses on automating the deployment process, ensuring seamless integration and delivery of the application.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/Abdelrahman-17/django_notes_app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`



![project-djanjo-notes](https://github.com/Abdelrahman-17/django_notes_app/assets/83679041/f0c9edd4-a5f2-4b6a-95a9-dc987e2a2497)





https://github.com/Abdelrahman-17/django_notes_app/assets/83679041/2e7cd495-6084-4e0f-893d-2acb3bb4c43b



