# Elixir Image

Docker Image para elixir con image magick.

## Generar imagen de docker.

```shell
docker build --tag codigobicentenario/elixir:image-magick .
```

## Corremos un contenedor y entramos al shell.

```shell
docker run --rm -ti codigobicentenario/elixir:image-magick sh
```
