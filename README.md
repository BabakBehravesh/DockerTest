This is an accompaying demo project for a "Docker in 1 hour" crash course on YouTube: https://www.youtube.com/@TechWorldwithNana

To run the container:
- clone the repo, and go to the root folder of the project
- run -> docker build -t node-app:1.0 .  pay attention to . which means from the current folder
- run -> docker run -d -p 3000:3000 node-app:1.0
- get the container id by running -> docker ps
- run -> docker logs <container id>


We can also use commands 
> docker-compose up -d
> docker-compose down
after since adding docker-compose.yaml file. 
