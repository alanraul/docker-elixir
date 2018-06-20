# Elixir Image

Docker Images para elixir construidas con Ubuntu.

## Generar imagen de docker.

```shell
docker build --tag codigobicentenario/elixir:ubuntu .
```

## Corremos un contenedor y entramos al shell.

```shell
docker run --rm -ti codigobicentenario/elixir:ubuntu sh
```
