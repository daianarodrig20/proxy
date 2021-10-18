## Proxy inverso

El proxy inverso es el servidor encargado de mostrar contenido de uno o más servidores que, a su vez, permanecen ocultos del cliente o usuario.

Los proxys inversos son una opción para incrementar la seguridad.
Asimismo, un proxy inverso resulta práctico para servir múltiples aplicaciones web desde una misma máquina.


### Balancear la carga
Un solo servidor de origen no puede manejar todo el tráfico entrante de un sitio web con millones de visitantes únicos diarios. En estos casos, puede distribuir el tráfico de forma inteligente entre un grupo de muchos servidores.
Un proxy inverso es una gran forma de configurar esto, ya que puede recibir el tráfico entrante antes de que llegue al servidor de origen. Si el servidor de origen está sobrecargado o cae completamente, puede distribuir el tráfico a otros servidores sin afectar la funcionalidad del sitio.
Los proxies inversos también pueden dirigir las solicitudes entrantes a varios servidores, y cada servidor realiza una función específica para la que está optimizado. El proxy inverso puede entonces recoger las respuestas de todos los servidores y entregarlas al cliente.

Los proxies inversos pueden ocultar la dirección IP y otras características de los servidores de origen. Así, el servidor de origen de tu sitio web puede mantener mejor su anonimato, aumentando su seguridad de manera significativa.

Requisitos para crear un proxy inverso con NGINX:
- Disponer de acceso root a un servidor linux.
- Tener instalado y activado Nginx. Asegurarse de no tener los puertos 80 y 443 ocupados por otro proceso como, por ejemplo, Apache.
- Tener corriendo una aplicación web en localhost a través de un puerto arbitrario y que esté disponible (por ejemplo el puerto 4000). Esto se puede lograr fácilmente con NodeJs o .NET Core.



## Bibliografia
- https://www.swhosting.com/es/comunidad/manual/como-crear-un-proxy-inverso-con-nginx

- https://kinsta.com/es/blog/proxy-inverso/
