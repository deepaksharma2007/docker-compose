# docker-compose project

### Project-Description

Deploy Basic sample application using docker compose.(Can be java, nodejs, php or python
etc..)
-Also Run a Database container using Docker-compose(MySQL or mongo).
-Mount root volume for those containers to host (bind mount)
-Host this setup on AWS EC2 instance.(You can create your AWS free tier account)
-Launch this instance in the new VPC rather than default VPC (Optional)
-Create new user on same EC2 server
-Enable ssh key based authentication for new user with the new ssh key
-Open only port 80 , 443 and the DB port for all. All other ports should be not be accessible
-Attach the elastic IP on the EC2 instance



