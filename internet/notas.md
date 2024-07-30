

# como funciona internet?

## introduccion

una red es un grupo de computadores u otros dispositivos que estan 
conectados entre si 

## como funciona internet una vision general

internet funciona conectando dispositivos y sistemas informaticos entre si mediante un conjunto de protocolos estandarizados
que define como se intercambia la informacion entre dispositivos y garantizan que los datos se transmitan de forma fiable y segura


cuando se envia datos a traves de internet se dividen en pequeños paquetes que se envian desde su dispositivo a un enrutador 
el router examina el paquete y lo reenvia al siguite router


para garantizar el envio de paquetes se utilian varios protocolos de internet (IP) y protocolo de control de transmision (TCP) 
## que es un protocolo
es un conjunto de reglas y estandares que definen comos e intercambia la informacion entre dispositivos y sistemas

IP: envia y enruta los paquetes a su destino correcto
TCP: hace que los paquetes se transmita de manera confiable y en orden correcto

otros protocolos importates
DNS: sistema de nombre de dominio
HTTP: protoco de transferencia de hipertexto
SSL/TLS: secure sockest layer / Transport layer segurity

## El papel de los protocolos en Internet
Los protocolos desempeñan un papel fundamental a la hora de permitir la comunicación y el intercambio de datos a través de Internet.


IP: envia y enruta los paquetes a su destino correcto
TCP: hace que los paquetes se transmita de manera confiable y en orden correcto
DNS: sistema de nombre de dominio
UDP: Protocolo de datagramas de usuario

## Conceptos basico y terminologia

- Paquete: Pequeña unidad de datos que se transmite a través de Internet.
- Enrutador: Un dispositivo que dirige paquetes de datos entre diferentes redes.
- Dirección IP: Un identificador único asignado a cada dispositivo en una red, utilizado para enrutar datos al destino correcto.
- Nombre de dominio: Un nombre legible que se usa para identificar un sitio web, como google.com.
- DNS: El Sistema de Nombres de Dominio se encarga de traducir los nombres de dominio en direcciones IP.
- HTTP: El protocolo de transferencia de hipertexto se utiliza para transferir datos entre un cliente (como un navegador web) y un servidor (como un sitio web).
- HTTPS: Una versión cifrada de HTTP que se utiliza para proporcionar una comunicación segura entre un cliente y un servidor.
- SSL/TLS: Los protocolos de seguridad Secure Sockets Layer y Transport Layer se utilizan para proporcionar una comunicación segura a través de Internet.

## Descripción de las direcciones IP y los nombres de dominio

son conceptos importantes que hay que entender cuando se trabaja con internet

IP es un indentificador unico asignado a cada dispositivo de una red
se utiliza para enrutar los datos al destino correcto
IP suelen representarse como una serie de cuatro números separados por puntos, como "192.168.1.1".

Los nombres de dominio, por otro lado, son nombres legibles por humanos que se utilizan para identificar sitios web y otros recursos de Internet. Por lo general, se componen de dos o más partes, separadas por puntos. Por ejemplo, "google.com"

## Introducción a HTTP y HTTPS

HTTP (Protocolo de transferencia de hipertexto) y HTTPS (HTTP seguro) son dos de los protocolos más utilizados en aplicaciones y servicios basados en Internet.

HTTP es el protocolo utilizado para transferir datos entre un cliente (como un navegador web) y un servidor (como un sitio web). Cuando visita un sitio web, su navegador web envía una solicitud HTTP

HTTPS es una versión más segura de HTTP, que encripta los datos que se transmiten entre el cliente y el servidor mediante el cifrado SSL/TLS


## Creación de aplicaciones con TCP/IP

TCP/IP (Protocolo de control de transmisión/Protocolo de Internet) es el protocolo de comunicación utilizado por la mayoría de las aplicaciones y servicios basados en Internet. Proporciona una entrega de datos fiable, ordenada y con comprobación de errores entre aplicaciones que se ejecutan en diferentes dispositivos.

Al crear aplicaciones con TCP/IP, hay algunos conceptos clave que se deben entender:
- Puertos: Los puertos se utilizan para identificar la aplicación o el servicio que se ejecuta en un dispositivo.
- Sockets: Un socket es una combinación de una dirección IP y un número de puerto, que representa un punto final específico para la comunicación. Los sockets se utilizan para establecer conexiones entre dispositivos y transferir datos entre aplicaciones.
- Conexiones: Se establece una conexión entre dos enchufes cuando dos dispositivos quieren comunicarse entre sí. 
- Transferencia de datos: Una vez que se establece una conexión, los datos se pueden transferir entre las aplicaciones que se ejecutan en cada dispositivo.

## Protección de la comunicación por Internet con SSL/TLS

Como hemos comentado anteriormente, SSL/TLS es un protocolo utilizado para cifrar los datos que se transmiten a través de Internet. Se usa comúnmente para proporcionar conexiones seguras para aplicaciones como navegadores web

Al utilizar SSL/TLS para proteger la comunicación por Internet, hay algunos conceptos clave que hay que entender:
- Certificados: Los certificados SSL/TLS se utilizan para establecer la confianza entre el cliente y el servidor
- Apretón de manos: Durante el proceso de protocolo de enlace SSL/TLS, el cliente y el servidor intercambian información para negociar el algoritmo de cifrado y otros parámetros para la conexión segura.
- Encriptación: Una vez que se establece la conexión segura, los datos se cifran mediante el algoritmo acordado y se pueden transmitir de forma segura entre el cliente y el servidor.


# Que es HTTP?


# nombre de un dominio 

un localizador uniforme de recursos (URL) contiene el nombre de dominio de un sition asi como otra informacion incluido el protocolo y la ruta por ejemplo: 

https://cloudflare.com/learning/

cloudflare.com : es el nombre del dominio
https: es el protocolo
/learning/: es la ruta de la pagina 
