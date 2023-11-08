# docker-postgres

## Prerequisitos
Otorgar permisos para ejecutar docker:

```
dockerd-rootless-setuptool.sh install
```
<br>

## Instalación

Descargar [docker-compose.yml](https://github.com/benigaslo/docker-postgres/raw/main/docker-compose.yml)

<br>

## Iniciar servicios
Ir a la carpeta donde está el docker-compose.yml y ejecutar:

```
docker compose up
```

## Uso

Navegar a http://localhost:8080.

<br>

## Login  

* `admin@admin.com` / `admin`

![](login.png)

<br>

## Conectar al servidor Postgres

* Ir al menú Object > Register > Server...

![](register1.png)

<br>

* General > name : `postgres_$USER`

![](register2.png)

<br> 

> [!NOTE]
> Sustituir $USER por el nombre de usuario del sistema

<br>

* Connection > Host name/address : `postgres_$USER`

* Connection > Username : `admin`

* Connection > Password : `admin`

![](register3.png)
