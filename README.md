# ci-cd-python - Commands to install Docker on EC2 
- Ensure port 80 is available
```
sudo yum update -y
sudo amazon-linux-extras install docker
sudo service docker start
sudo systemctl start docker
sudo service docker status
sudo groupadd docker
sudo usermod -a -G docker ec2-user
newgrp docker
docker —-version
```