# π° docker-compose project π°

πIn this I create multi-tier application using Docker-compose. By just one click , we get entire infrastructure of multi-tier application.

πI create one container for wordpress app and one for mysql database . Also attach docker volume , So that data of both will be persistent. 

### Project-Description

π Deploy Basic sample application using docker compose.(Can be java, nodejs, php or python etc..)

π Also Run a Database container using Docker-compose(MySQL or mongo).

π Mount root volume for those containers to host (bind mount)

π Host this setup on AWS EC2 instance.(You can create your AWS free tier account)

π Launch this instance in the new VPC rather than default VPC (Optional)

π Create new user on same EC2 server

π Enable ssh key based authentication for new user with the new ssh key

π Open only port 80 , 443 and the DB port for all. All other ports should be not be accessible

π Attach the elastic IP on the EC2 instance



