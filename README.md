## Crea la imagen conforme al contenido de Dockerfile
```
docker build -t app-mia  .
```
## Crear la imagen conforme al contenido de Dockerfile  y el nombre del archivo no es el default
```
docker build -t app-mia  . -f Dockerfile01
```

## Ingresamos al S.O. del contenedor creado
```
docker run -it app-mia sh
```