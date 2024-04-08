# Docker-React-Vite-setup
My steps for hosting a React Vite application on repository

Import:
vite.config.js (IMPORTANT)
Dockerfile
gitignore
{modify to suit additional needs}

Building image:
sudo docker build --tag {name} .

Sharing image:
sudo docker tag {name} {username}/{name}
sudo docker push {username}/{name}

Running:         (Ex. 8080:8080) 
sudo docker run -p {port:port} {name}
