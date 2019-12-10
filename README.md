# project-testing

maven commands
maven goals
clean install package

Docker commands
docker build -t $JOB_NAME:v1.$BUILD_ID .
docker tag $JOB_NAME:v1.$BUILD_ID ashwaqar/$JOB_NAME:v1.$BUILD_ID
docker tag $JOB_NAME:v1.$BUILD_ID ashwaqar/$JOB_NAME:latest
docker push ashwaqar/$JOB_NAME:v1.$BUILD_ID
docker push ashwaqar/$JOB_NAME:latest
docker rmi $JOB_NAME:v1.$BUILD_ID ashwaqar/$JOB_NAME:v1.$BUILD_ID ashwaqar/$JOB_NAME:latest

Ansible commands
ansible-playbook create_docker_container.yml
