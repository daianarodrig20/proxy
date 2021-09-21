El proxy inverso es el servidor encargado de mostrar contenido de uno o más servidores que, a su vez, permanecen ocultos del cliente o usuario.

Los proxys inversos son una opción para incrementar la seguridad.

Requisitos para crear un proxy inverso con NGINX:
- Disponer de acceso root a un servidor linux.
- Tener instalado y activado Nginx. Asegurarse de no tener los puertos 80 y 443 ocupados por otro proceso como, por ejemplo, Apache.
- Tener corriendo una aplicación web en localhost a través de un puerto arbitrario y que esté disponible (por ejemplo el puerto 4000). Esto se puede lograr fácilmente con NodeJs o .NET Core.


https://www.swhosting.com/es/comunidad/manual/como-crear-un-proxy-inverso-con-nginx
