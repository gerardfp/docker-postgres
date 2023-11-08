# docker-postgres

## Prerequisitos
Otorgar permisos para ejecutar docker

```
dockerd-rootless-setuptool.sh install
```

## Instalación

Descargar [docker-compose.yml](https://github.com/benigaslo/docker-postgres/raw/main/docker-compose.yml)

# Iniciar servicios
Ir a la carpeta donde está el docker-compose.yml y ejecutar:

```
docker compose up
```

# Uso

Navegar a http://localhost:8080.

## Login  

* admin@admin.com / admin

![](login.png)

## Conectar al servidor Postgres

* Ir al menú Object > Register > Server...

![](register1.png)

* General > name : "postgres_$USER"

![](register2.png)

* Connection > Host name/address : "postgres_$USER"

* Connection > Username : "admin"

* Connection > Password : "admin"

![](register3.png)
