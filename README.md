# Herbal Doctor Chatbot code(end to end)

Herbal-EcoDoc is an AI assistant that assists you in treating common diseases with homemade remedies. It provides you a recipe with what you can make your own medicine at home. 

![ecodoc](https://github.com/user-attachments/assets/a08b7707-a0b0-4688-9d87-753cf750702c)


# STEPS:
# Git clone the repository

``` bash
Project repo: https://github.com/sm-ak-r33/Herbal-EcoDoc.git
```
# Create an environment
```bash 
conda create -n HerbalDoc python=3.10 -y
```

```bash
conda activate HerbalDoc
```

# Install the requirements
```bash
pip install -r requirements.txt 
``` 

# Run locally 
```bash
python app.py
```
Runs on localhost:8080

# CI/CD on AWS EC2 
```bash
sudo apt-get update -y
``` 
```bash
sudo apt-get upgrade
```
```bash
curl -fsSL https://get.docker.com -o get-docker.sh
```
```bash
sudo sh get-docker.sh
```
```bash
sudo usermod -aG docker ubuntu
```
```bash
newgrp docker
```

Github Secrets:

```bash
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
AWS_DEFAULT_REGION
ECR_REPO
PINECONE_API_KEY
OPENAI_API_KEY
```
