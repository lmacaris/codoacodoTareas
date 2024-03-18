
# Tarea - 1 Codo a codo 

### Introduccion

1- ¿Por qué no utilizamos Microsoft Word para escribir el código de una página web?

Cuando se utiliza Microsoft Word para crear tu contenido HTML, el editor de texto genera un código adicional (código basura) que no es necesario y que no beneficiará a tus envíos. Este código podría romper el diseño o incluso hacer que algunos ISP pueden bloquear a tu empresa a causa de SPAM - Existe una forma de habilitar la opion de programador. Cómo hacerlo?
En la pestaña Archivo , ir a Opciones > Personalizar cinta de opciones. En Personalizar la cinta de opciones y Pestañas principales, active la casilla Programador.

2- ¿Cuál es la diferencia entre Front-End, Back-End y FullStack?

Un desarrollador Full Stack es alguien que trabaja tanto con el front-end como con el back-end de una aplicación web. El front-end es responsable de la apariencia visual del sitio web, mientras que el back-end es responsable de la lógica y la infraestructura detrás de escena del sitio

### Internet 

1- ¿Qué otros protocolos además del TCP/IP existen

Existen muchos protocolos pero algunos de comunicación asociados a internet son POP, SMTP, HTTP (siendo reemplazado por) HTTPS, DNS, DHCP, IP, ICMP, ETHENET entre otros.

2- ¿El envío de un email puede considerarse un uso de internet?

El correo electrónico o e-mail es un servicio en línea que, al igual que ocurre con el correo postal tradicional, nos permite enviar y recibir mensajes a través de un servicio de red a múltiples destinatarios.

3- ¿Qué diferencia hay entre consultar mis mails por la web de gmail.com a consultarlos
desde la aplicación de celular? ¿Se utilizan los mismos protocolos?

#### Interfaz web de Gmail (gmail.com):
Protocolo utilizado: Cuando accedes a Gmail a través de la interfaz web, utiliza principalmente protocolos abiertos como POP3 (Post Office Protocol 3) e IMAP (Internet Message Access Protocol).
Funcionalidad:
Puedes leer, redactar y gestionar tus correos electrónicos en línea.
Admite varias cuentas.
Permite ver y guardar archivos adjuntos.
Ofrece funciones como notificaciones de etiquetas.
Usabilidad sin conexión: Puedes acceder a Gmail sin conexión a través de la interfaz web, pero requiere configurar previamente el modo sin conexión.

#### Aplicación móvil de Gmail (App):
Protocolo utilizado: La aplicación móvil de Gmail habla el protocolo propio de Gmail con el servidor de Gmail. No utiliza directamente POP3 ni IMAP.
Funcionalidad:
Diseñada específicamente para cuentas de Gmail.
Maneja eficazmente funciones específicas de Gmail como etiquetas, archivado y envío de correos electrónicos desde alias.
Admite varias cuentas, incluidas las de Gmail y Google Apps.
Generalmente más rápido y con mayor capacidad de respuesta debido a su protocolo especializado.
Uso sin conexión: La aplicación de Gmail también permite el acceso sin conexión a tus correos electrónicos, incluso sin una conexión activa a Internet.

En resumen:

Si sólo tienes una cuenta de Gmail y das prioridad a las funciones específicas de Gmail, la app de Gmail es una gran elección.
Si utilizas varias cuentas o cuentas que no son de Gmail, la interfaz web (gmail.com) con sus protocolos abiertos (IMAP/POP3) es más versátil.
Recuerda que ambas opciones proporcionan acceso seguro a tus correos electrónicos, ¡pero la elección depende de tus preferencias y necesidades!

### HTML

1 ¿Hay más de una forma de cambiar el color de un texto?

Si, existen distintas formas de cambiar el color de un texto. Podemos utilizar la propiedad "color" en la linea de texto dentro de la etiqueta <font> especificanto el nombre del color o de forma hezadecimal. 
		Ejemplo :
 
        <font color="#800080">This text is purple.</font>

        Tambien podemos utilizar CSS en linea, parecido al anterior solo que debemos utlizar la propiedad "style=''" dentro de la etiqueta <font> y con la particularidad de he podemos especificar el nombre del color, usar hexadecimal, RGB o hsl
	Ejemplos:
     <p style="color: purple">This is a purple paragraph.</p>
		  <p style="color:#800080">This is a purple paragraph.</p>
		  <p style="color:RGB(153,0,255)">This is a purple paragraph.</p>
		  <p style="color:hsl(276, 100%, 50%)">This is a purple paragraph.</p


	    Tambien podemos usar CSS incrustado (nombre, ,hexadecimal, RGB o HSL :

	<!DOCTYPE html>
		<html>
		<head>
  		<style>
		    <p> {
		        color: purple;
 		   }
		</style>
		</head>


	CSS externo:

		body {color: purple;}



2 - ¿Puedo centrar un texto en forma vertical en una página web?

Es posible centrar un texto de forma vertical. Unas de las formas seria en una pagina web utilizando la propiedad de CSS "display: flex". Esta propiedad "display: flex" en el contenedor que envuelve al texto. Luego, se utiliza "align-items: center" y "justify-content: center" para alinear el contenido tanto vertical como horizontalmente.
	
	Ejemplo : 
		<div class="contenedor">
		<div class="centrado-vertical">
		<p>¡Texto centrado en vertical!</p>
		</div>
		</div>>

		- CSS -

		.contenedor {
		display: flex;
		align-items: center;
		justify-content: center;
		height: 100vh;
		}

		.centrado-vertical {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		}

3 - ¿Qué otras secciones además de Header y Body existen en una página web ?

Existen otras secciones que fueron incorporadas con HTML5 como por ejemplo <article>, <section>, <nav>, <aside>, <header> y <footer> (y también la etiqueta <main>, aunque esta no se considere una etiqueta de sección sino de bloque). Creando una estructura similar al siguiente ejemplo dependiendo de como se construya la pagina web:

![image](https://www.aulaclic.es/html/graficos/estructura_pagina_web.png)
<img src="https://www.aulaclic.es/html/graficos/arbol-html.svg" width="200" height="400" />