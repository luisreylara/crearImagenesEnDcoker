## Crea la imagen conforme al contenido de Dockerfile
```
docker build -t app-mia  .
```
## Crear la imagen conforme al contenido de Dockerfile  y el nombre del archivo no es el default
```
docker build -t app-mia  . -f Dockerfile01
```

## Crear la imagen conforme al contenido de Dockerfile  , el nombre del archivo no es el default y se crea un tag con version
```
docker build -t app-mia:1.0.0  . -f Dockerfile01
```

## Ingresamos al S.O. del contenedor creado
```
docker run -it app-mia sh
```
## Ingresamos al S.O. del contenedor creado con un TAG especifico
```
docker run -it app-mia:1.0.0 sh
```
