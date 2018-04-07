# DOCKER

### Comandos Docker Utiles

Lista todas las imagenes iniciadas

```
docker ps -s
```

Lista todas las imagenes 

```
docker images -a
```

Para una imagenes

```
docker stop <imgID>
```

Elimina todas las imagenes paradas

```
docker rmi $(docker images -a -q) -f
```

Limpia todas las imagenes de memoria y disco

```
docker system prune
```


Lanza imagen de docker

```
docker-compose up -d
```
