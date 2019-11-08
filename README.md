# GitLab_CI-CD
GitLab CI/CD

  apt-get update && apt-get upgrade && apt-get install htop iotop mc tree figlet ssh
  apt-get update && apt-get upgrade -y

 apt-get install docker.io
sudo apt-get install gitlab-runner

 sudo gitlab-runner register

 gitlab-runner restart



 sudo curl -L "https://github.com/docker/compose/releases/download/1.24.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

 sudo chmod +x /usr/local/bin/docker-compose

 sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose

 docker-compose --version

 

 sudo usermod -aG docker gitlab-runner

  docker images

  nano /etc/gitlab-runner/config.toml 

  gitlab-runner restart

