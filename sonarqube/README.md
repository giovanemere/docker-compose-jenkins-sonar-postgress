# Prerrequisitos

# Uso de repositorio

se creo carpeta docker-compose para agregar subcarpeta por aplicacion

## Sonarqube

```
sudo chmod -R 777 /home/giovanemere/docker
cd /home/giovanemere/docker/docker-compose/sonarqube
sudo docker-compose -f sonarqube.yml up -d
```

Revisar Imagen

```
docker exec -it sonarqube bash
```

revisar estado del servicio

```
sudo docker logs sonarqube
```

## Permisos de Firewall

```
9001/tcp
9092/tcp
```

## Create Databases:

Acceder a la base de datos y crear bases de datos:

```
docker exec -it atlassian_database_1  psql -U postgres
	CREATE DATABASE sonarqube;
      	\l
      	\q
```


## Browse Jenkins products:

URL:   http://192.168.137.5:3000


```
docker exec -it jenkins_jenkins-devops_1 cat /var/jenkins_home/secrets/initialAdminPassword
```
