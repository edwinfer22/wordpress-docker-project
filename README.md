# WordPress Docker Project

This project runs a WordPress site using Docker and Docker Compose. It includes a WordPress service and a MySQL database service.

## Prerequisites

- Docker
- Docker Compose

## Paso a Paso

1.  **Clonar el Repositorio:**
    Obtén una copia del proyecto en tu máquina local.
    ```sh
    git clone https://github.com/edwinfer22/wordpress-docker-project.git
    cd wordpress-docker-project
    ```

2.  **Iniciar los Servicios:**
    Usa Docker Compose para levantar los contenedores en segundo plano.
    ```sh
    docker-compose up -d
    ```

3.  **Instalación de WordPress:**
    Abre tu navegador y ve a `http://localhost:8000`. Verás la página de instalación de WordPress. Sigue las instrucciones para configurar el título del sitio, tu usuario y contraseña.

    ![Pantalla de Instalación de WordPress](images/Wordpress.jpg)

4.  **¡Listo!**
    Tu sitio de WordPress está funcionando.

## Accessing the Site

Once the containers are running, you can access the WordPress installation by navigating to the following URL in your web browser:

[http://localhost:8000](http://localhost:8000)

## Stopping the Services

To stop all the running services, use the command:

```sh
docker-compose down
```
