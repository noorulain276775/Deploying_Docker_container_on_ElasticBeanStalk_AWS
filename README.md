# Deploying_Docker_container_on_ElasticBeanStalk_AWS

commands
1. docker build .
2. docker tag <image_id> <name>:<tag> i.e nooribraim/ebs:latest is name and tag here
3. docker run -p 8080:80 nooribrahim/ebs:latest

 or 

1. docker build -t <name>
2. docker run --name nginx -p 8080:80 <name>
