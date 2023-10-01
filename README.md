# docker-compose-jenkins-sonar-postgress

Repositorio docker-compose Devops

Contiene imagenes Docker

* Jenkins
* Postgres
* Sonarqube community

En cada carpeta de los compose cuenta con un archivo command el cual tienen los comandos que se requieren por cada app

# Prerequisitios

## Instalar Docker CE

```
sudo apt-get update -y

sudo apt install apt-transport-https ca-certificates curl software-properties-common -y

curl -fsSL [https://download.docker.com/linux/ubuntu/gpg](https://download.docker.com/linux/ubuntu/gpg) | sudo apt-key add -

sudo add-apt-repository "deb [arch=amd64] [https://download.docker.com/linux/ubuntu](https://download.docker.com/linux/ubuntu) focal stable" -y

sudo apt update -y

apt-cache policy docker-ce -y

sudo apt install docker-ce -y

sudo systemctl enable docker

sudo systemctl start docker

docker -version
```


## Instalar Docker Compose

```
sudo curl -L "https://github.com/docker/compose/releases/download/1.26.2/docker-compose-(uname-s)-(uname−s)−(uname -m)" -o
/usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
```
