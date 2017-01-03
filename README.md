## apesconsole-docker
Demo Application dockerised to show the basic Docker deployment
The code case be deployed to any Linux OS. I prefrered AWS EC2 and Digital Ocean

## Run Application
1. apt-get update
2. apt-get insall docker docker.io
3. Clone the Git Code base
4. cd apesconsole-docker/
5. docker build -t demo-app
6. docker images
7. docker run -p 8080:8080 demo-app

