# Prerequisitos

# Uso de repositorio

se creo carpte docker-compose para agregar subcarpeta por aplicacion

## Jenkins

```
sudo chmod -R 777 /home/giovanemere/docker
cd /home/giovanemere/docker/docker-compose/jenkins
sudo docker-compose -f jenkins.yml up -d
```

Revisar Imagen 

```
docker exec -it a3b42cb4750c bash
```

## Permisos de Firewall

```
8091/tcp
8491/tcp
50000/tcp
```

## Browse Jenkins products:

URL: 

usuario:

password:
