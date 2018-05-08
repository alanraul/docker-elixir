# Elixir Image

Docker Images para elixir construidas con Alpine Linux.

## Generar imagen de docker.

```shell
docker build --tag codigobicentenario/elixir:latest .
```

## Corremos un contenedor y entramos al shell.

```shell
docker run --rm -ti codigobicentenario/elixir:latest sh
```
