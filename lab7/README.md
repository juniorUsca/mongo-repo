
Para iniciar las maquinas usar:
```
docker-compose up
```

Para detenerlo ponse:
```
Ctrl+C
```

Para conectarse a una maquina usar:
```
docker ps
docker exec -it <nombre del contenedor> bash
```

Para salir de la maquina usar:
```
exit
```

Para copiar el archivo zip.json usar:
```
docker cp zips.json <nombre del contenedor>:/zip.json
ejemplo:
docker cp zips.json lab7_mongo-pri_1:/zip.json
```
