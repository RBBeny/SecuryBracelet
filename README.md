# DesarrolloParaDispositivosInteligentes

## Nombre del Proyecto: Security Bracelet

### Objetivo:

Security bracelet es un brazalete para ayudar en un momento de peligro. De manera que en una situación de peligro, 
el usuario podrá activar las funcionalidades configuradas en el brazalete, pues
al momento en que el usuario enviara un correo de ayuda. El brazalete tendrá la capacidad de identificar la ubicacion 
con el modulo de gps y mostrarlo en la pantalla y ademas de dar la hora como otros relojes



### Problemática que resuelve:

La inseguridad constituye uno de los grandes problemas de México. Se manifiesta en dos formas: la inseguridad que vive
la población, afectada por el aumento de los delitos, y el auge del narcotráfico, que se explica por la incorporación 
de México a la ruta de la cocaína proveniente de Colombia con destino a Estados Unidos. Esto se manifiesta diariamente 
en una creciente violencia, concentrada en los enfrentamientos entre organizaciones criminales y entre estas y las 
fuerzas de seguridad. El artículo argumenta que, aunque no puede hablarse de México como un «Estado fallido», las 
estructuras de seguridad, inteligencia y justicia se encuentran sobrepasadas y corrompidas, y es necesario encarar
prontamente su reforma si se quiere enfrentar el problema.


### Epicas:


*	Yo como usuario quiero que mi brazalete de seguridad se active al escuchar una palabra clave configurada previamente, para que el brazalete active las diferentes funcionalidades.
*	Yo como usuario quiero que mi brazalete de seguridad pueda grabar audio, para poder activar el brazalete y grabar algún audio que sirva de referencia en caso de que me encuentre en un momento de peligro y se envíe a mi contacto de emergencia, alertando que me encuentro en peligro.
*	Yo como usuario quiero que mi brazalete de seguridad pueda tomar fotografía, para poder capturar alguna imagen que sirva como referencia en caso de que me encuentre en un momento de peligro, y se envíe a mi contacto de emergencia, alertando que me encuentro en peligro.
*	Yo como usuario quiero que mi brazalete de seguridad contenga mi ubicación como referencia en caso de que me encuentre en un momento de peligro y se envíe a mi contacto de emergencia, alertando que me encuentro en peligro.
*	Yo como usuario quiero que mi brazalete de seguridad contenga una pequeña pantalla para que me muestre mi ubicación, para que me sirva para precisar donde me encuentro.

### Materiales:
| Nombre     | Descripción | Imagen | Cantidad|
| ---------- | ------ | --------| ------ |
| ESP-8266    | Modulo wifi con camara | ![alt text](https://media.naylampmechatronics.com/474-medium_default/nodemcu-v2-esp8266-wifi.jpg) | 1 |
| ESP-8266 | Modulo para programar en el Modulo wifi | ![alt text](https://media.naylampmechatronics.com/474-medium_default/nodemcu-v2-esp8266-wifi.jpg) | 1 |
| Pantalla Oled     | Modulo de sensor de sonido | ![alt text](https://www.luisllamas.es/wp-content/uploads/2016/11/arduino-pantalla-oled-esquema.png) | 1 |
| Neo-6m     | Modulo Gps | ![alt text](https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcRfqi2PJ0tNBLSzyX_7u-lzNtm2CjN-2dTO5MmD2eGg3uD5kBU-AMJ5e6lcWyvewelaoiyw7vJl8Rsougr_ZvLb14qdcX2L) | 1 |
|       Bateria     | Para dar energia al prototipo | ![alt text](https://www.steren.com.mx/media/catalog/product/cache/532829604b379f478db69368d14615cd/image/21920955a/power-bank-de-20-000-mah-con-turbo-charge-qc-y-power-delivery-con-2-salidas-usb-y-usb-c.jpg) | 1 |

## Software a utilizar:

| Nombre | Licencia | Descripción |
| -------|----------| ----------|
| IDE Arduino | Software libre | IDE es un conjunto de herramientas de software que permiten a los programadores desarrollar y grabar todo el código necesario para hacer que nuestro Arduino funcione como queramos. |
| GitHub | Software libre | La plataforma está creada para que los desarrolladores suban el código de sus aplicaciones y herramientas, y que como usuario no sólo puedas descargarte la aplicación |
| Google Maps | Libre de menos de 10000 solicitudes | Nos funciona para mostrar la ubicacion con las cordenadas que nos proporciona el sensor |

### Diagrama a utilizar


![alt text](
https://github.com/RBBeny/SecuryBracelet/blob/main/diagrama.png?raw=true)

### Diagrama de componente

![alt text](https://github.com/RBBeny/SecuryBracelet/blob/main/diagramadibujado.jpeg?raw=true)


### Tablero Trello

https://trello.com/invite/b/wA4FDrtI/514772325cf0dbe6b85bacafde44e1c5/security-bracelet

![alt text](https://github.com/RBBeny/SecuryBracelet/blob/main/trello.jpg?raw=true)

## Prototipo sprint 2 
![alt text](https://github.com/RBBeny/SecuryBracelet/blob/main/sprint2.jpeg?raw=true)

## Prototipo final 

Es todo completo con las funcionalidades terminadas y funcionando autonamente sin necesidad de tenerlo conectado a la computadora
![alt text](https://github.com/RBBeny/SecuryBracelet/blob/main/sprint3.jpeg?raw=true)


## Carcasa en 3d, diseño

La carcasa la imprimimos con la impresora 3D que se encuentra en las instalaciones de la universidad 
![alt text](https://github.com/RBBeny/SecuryBracelet/blob/main/impresion3d.jpeg?raw=true)

## Captura de aplicacion web para mostrar los datos
En esta pagina mostramos datos que se envian en tiempo real como lo son las cordenadas y fecha y hora, ademas un link para abrir el mapa con la ubicación

![alt text](https://github.com/RBBeny/SecuryBracelet/blob/main/paginaweb.jpeg?raw=true)

## Envio de correo
Se envia un correo con el link de la ubicacion y asi el destinatario pueda ver donde se encuantra

![alt text](https://github.com/RBBeny/SecuryBracelet/blob/main/emails.jpeg?raw=true)

## Ver Ubicación en el maps

Se marca un marcador y para esto se utilizo la libreria de google maps

![alt text](https://github.com/RBBeny/SecuryBracelet/blob/main/mapsa.jpeg?raw=true)
