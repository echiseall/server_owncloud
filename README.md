BIENVENIDO

1. Clonar el directorio server_owncloud del repositorio GitHub

git clone https://github.com/echiseall/server_owncloud.git

2. Editar el archivo de configuracion .env con los datos de usuario y contraseña deseados

vim .env

"

OWNCLOUD_VERSION=10.8

OWNCLOUD_DOMAIN=localhost:80

ADMIN_USERNAME=usuario

ADMIN_PASSWORD=contrasena

HTTP_PORT=80


"

3. Poner en marcha el container
docker-compose up -d

4. Comprobar que todos los contenedores se han iniciado correctamente

docker-compose ps

5. Deberá ver una salida similar a la siguiente:

 ![image](https://user-images.githubusercontent.com/90971034/142946481-00009eb4-db62-4d49-bcc3-d2c1d00c45d1.png)


6. Iniciar sesión abriendo en el navegador el puerto 80 y completando los datos ingresados en el .env 
 
http://localhost:80


