
## Docker Compose 📦
Docker Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration.
______________________________________________________________________________________________________________________________________________________________________________

## Installation:

1. Check docker-compose is available on system or not.
```
docker-compose -v
```
If, not
```
pip install -U docker-compose
```

2. Create docker-compose file in any location.
I have attached .yaml file with this folder.
```
mkdir DockerCompose

touch docker-compose.yaml
```

3.  Run Docker Compose
```
docker-compose up
```

#### This will start your application defined in docker-compose.yml and make it available at http://localhost:8080.
