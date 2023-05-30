# Para crear la imagen
```
docker build -t proyecto_bootcamp_edvai_jueves .
```

**-t:** tags

# Para crear el container
```
docker run -p 5000:5000 -e ID_USER=JFQ proyecto_bootcamp_edvai_jueves
```

**-p:** publish

**-e:** env -> Variable de entorno
