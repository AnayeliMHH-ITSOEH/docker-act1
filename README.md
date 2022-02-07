# docker-act1
Elaborado por: Anayeli Monserrat Hernández Herrera
- Levantar el CMS de Wordpress con salida en el puerto 8080 con conexión a la base de datos worpress01 creada en el contendor mariadb01. 
- Realizar la conexión empleando bridge FrontEnd y BackEnd, como se realizo en clase.
- Crear dos volumenes uno para wordpress llamado VL_wordpress01 compartido en el Host con la dirección /var/www/html y otro para mariadb01 llamado VL_mariadb01 compartida en el host con la dirección /var/lib/mysql, en donde se almacen la información de cada contener. 
