## Created EC2 instance using UI

## Install AWS CLI v2
```curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
sudo apt install unzip
unzip awscliv2.zip
sudo ./aws/install -i /usr/local/aws-cli -b /usr/local/bin --update
aws configure
```

## Install Docker
```
sudo apt-get update
sudo apt install docker.io
docker ps
sudo chown $USER /var/run/docker.sock
```
## Create ECR Repo using UI
## Clone the repository build Docker image and pushed to ECR
```
git clone https://github.com/santoshbd67/VE3-Assignment.git
cd VE3-Assignment
