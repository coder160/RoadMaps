
# HTTP

## Definición


> HTTP (Protocolo de Transferencia de Hipertexto) es la base de la comunicación de datos en la World Wide Web. Es un protocolo de capa de aplicación que define cómo se formatean y transmiten los mensajes entre navegadores web y servidores.

[Sobre Http... - Coder160.Medium](https://coder160.medium.com/sobre-http-07da4dbbcc2e)


### Cómo funciona Http

> HTTP opera en un modelo de solicitud-respuesta: los clientes (usualmente navegadores web) envían solicitudes a los servidores, los cuales responden con los datos solicitados

[Sobre Http... - Coder160.Medium](https://coder160.medium.com/sobre-http-07da4dbbcc2e)



### Http es ahora un estandar

En su momento, había dos protocolos de internet que podías elegir para trabajar. Incluso antes de la web, teníamos que enviar paquetes de información (o datagramas) de una máquina a otra a través de internet. Para un desarrollador de juegos, el protocolo importante era UDP (Protocolo de Datagrama de Usuario). Este era el estándar rápido y sin confirmación: enviabas un paquete a través de la red, se recibía, o a veces no. Era perfecto para representar (por ejemplo) una bala de un jugador de un juego que iba de tu arma, a través de la red, hasta mostrarse en la máquina del objetivo. Incluso si una bala se perdía en el camino, al menos la sesión de juego en conjunto estaría bien.

Pero para sistemas más estables como la web, el protocolo subyacente correcto era TCP (Protocolo de Control de Transmisión). Este era un sistema más formal, que garantizaba la entrega y el orden correcto de los paquetes. Así se creaban conexiones confiables y, más adelante, flujos confiables de información. Conectarse a internet antes de la web (sí, hubo un antes), recuerdo usar Trumpet Winsock, que era descrito como una “pila TCP/IP”. En una compañía ya desaparecida, lo usábamos para trabajar con CIX, que era un sistema de conferencias en línea británico (tablón de mensajes). Hoy en día, claro, CIX es una banda de chicos surcoreana. Eso es progreso.

Eventualmente, la World Wide Web y HTTP, escrito sobre TCP/IP, tomaron el control como el uso principal de internet. El otro acrónimo que falta es TLS (Seguridad de la Capa de Transporte), que proporcionaba el elemento de encriptación y se convirtió en el estándar de seguridad de facto cuando HTTP/2 estaba listo.

En esos días, la conexión entre las PC era generalmente por cable, y cualquier pérdida se debía al ruido en las antiguas líneas de cobre. TCP era bueno para controlar los paquetes errantes ocasionales. A medida que la web creció, las razones para usar UDP disminuyeron.



### Mas sobre Http

**HTTP/0.9 - Una sola línea (1991)**

La primera versión documentada de HTTP fue HTTP/0.9, propuesta en 1991. Era el protocolo más simple, con un solo método llamado GET. Si un cliente necesitaba acceder a alguna página en el servidor, haría una solicitud simple como la siguiente:

Y la respuesta del servidor se vería de la siguiente manera:

Es decir, el servidor recibiría la solicitud, respondería con el HTML y, tan pronto como se transfiriera el contenido, la conexión se cerraría. Como puedes ver, el protocolo realmente no era más que un trampolín para lo que estaba por venir.

**HTTP/1.0 - 1996**

En 1996, surgió la siguiente versión de HTTP, es decir, HTTP/1.0, que mejoró enormemente la versión original.

A diferencia de HTTP/0.9, diseñado solo para respuestas HTML, HTTP/1.0 ahora podía manejar otros formatos de respuesta, como imágenes, videos, texto plano o cualquier otro tipo de contenido.



## Fuentes

- [CloudFlare - Glosario Http](https://www.cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http/)

- [CS FYI - HTTP en Profundidad](https://cs.fyi/guide/http-in-depth)

- [thenewstack - Http es ahora un estandar](https://thenewstack.io/http-3-is-now-a-standard-why-use-it-and-how-to-get-started/)



