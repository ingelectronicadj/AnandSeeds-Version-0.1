# Soberania Alimentaria

<p align="center"><em><strong>APORTES PARA LA CUARTA REVOLUCION VERDE:</strong> Softaware y Hardware libre para una sociedad libre.</em></p>

### Nombre del proyecto: Revolución Verde Etnosoft ###

Este proyecto de desarrollo colaborativo, esta basado en [Métodologías ágiles para el desarrollo de software: eXtreme Programming (XP)](http://www.cyta.com.ar/ta0502/v5n2a1.htm)

### Descripción del proyecto ###

<p align="justify"> Este proyecto tiene como objetivo implementar un invernadero de 1mx1m, controlando variables de temperatura, ventilación, riego e iluminación desde una pagina web, para ser monitoreado desde un ordenador (PC-Portatil), tablet o movil que disponga conexion a internet.
Ademas, se utilizara un sistema fotovoltaico que alimente los circuitos eléctricos y electrónicos como fuente de energía alternativa.</p>

### Objetivos ###

* Implementar un sistema de acceso electromecánico que pueda ser utilizado facilmente como sistema de seguridad para nuestro invernadero
* Construir un sistema fotovoltaico como fuente para alimentar la circuitería electrónica del invernadero
* Generar una interfaz web sencilla que muestre información de los condiciones ambientales al interior del invernadero con accionamiento on/off de elementos de control
* Emplear unica y exclusivamente herramientas de software libre para el desarrollo del proyecto

### Materiales ###
![Energia LaunchPad](http://energia.nu/img/LaunchPadMSP430G2452-v1.5.jpg "MSP-EXP430G2 LaunchPad")
![Arduino](http://arduino-info.wikispaces.com/file/view/Mega2560_R3_Label-small-v2%20(2).png/471429496/800x526/Mega2560_R3_Label-small-v2%20(2).png "Arduino Mega")

1. Acceso electromecánico:
 * Microcontrolador Atmega328  
 * Programador arduino UNO  
 * Pantalla LCD 16x2  
 * Teclado 4x3  
 * Vaquela  

2. Circuito fotovoltaico  
 * MSP-EXP430G2 LaunchPad  
 * 2 Fotoresistencias  
 * Celdas solares 12V 200mAh  
 *  Bateria Recargable  
 * Servomotores  
 * 3 Diodos 1N4007  
 * 3 Capacitores cerámicos de 0.1uF  
 * Regulador LM317  
 * Regulador LM7805  
 * Triac de 100 ohmios  

3. Invernadero monitoreo web

 * Una placa Arduino como el Arduino Uno
 * Un escudo Arduino Ethernet
 * Un cable Ethernet, cable para conectar directamente a su router de red
 * Un cable USB para alimentar y programar el Arduino
 * Una tarjeta micro SD, por ejemplo, una tarjeta de 2 GB que es compatible SPI - sólo es necesario para algunos de los servidores
 * Una computadora con una ranura de tarjeta micro SD o un lector de tarjetas con una ranura para tarjeta micro SD - sólo se requiere
    para los servidores de la tarjeta SD


### Instrucciones para instalar, configurar, o ejecutar el programa ###

### Instalación IDE arduino   

El entorno de código abierto Arduino hace fácil escribir código y subirlo a la tarjeta. Se ejecuta en Windows, Mac OS X y Linux. El   
entorno está escrito en Java y basado en Processing, avr-gcc, y otro software de código abierto.  
Al descargar el software desde esta página, usted está de acuerdo con los términos especificados. Esta página contiene los enlaces 
de descarga en el último entorno de Arduino de desarrollo integrado (IDE) de software, notas de liberación, y software adicional que no se incluyen con el IDE

### Notas de instalación ###

Se debe descargar la libreria keypad.zip del siguiente enlace   

 * http://playground.arduino.cc/uploads/Code/keypad.zip
Ponga la carpeta del teclado en "arduino \ bibliotecas \". En el Arduino IDE, cree un nuevo dibujo (o uno abierto) y seleccione desde el menú de "Sketch -> Importar biblioteca -> Teclado". Una vez que la biblioteca es importado, aparecerá un "# include <Keypad.h>" línea en la parte superior de su Sketch.  

Para utilizar la librería Ethernet.h se debe configurar la IP de acuerdo a su red  

Determinar el rango de direcciones IP  

El rango de direcciones que el PC está utilizando debe ser determinado. El Arduino entonces se le asigna una dirección dentro de este rango que permitirá un navegador web en el PC para conectarse al servidor web Arduino.
### windows 7 ###

En Windows 7, haga clic en el icono de acceso a Internet en la barra inferior de Windows. Es posible que primero deba hacer clic en la pequeña "flecha hacia arriba" para el icono de la red que se muestra .  

Después de hacer clic en el icono de acceso a Internet, haga clic en Abrir redes y recursos compartidos en el cuadro que aparece.  

Ahora haga clic en Conexión de área local y, a continuación detalles ... en el cuadro de diálogo que aparece.  

En el cuadro de diálogo Conexión de red Detalles que aparece, la dirección IP de la PC se puede encontrar al lado de direcciones IPv4.  
### Linux ###

Para encontrar la dirección IP de un ordenador Linux, escriba lo siguiente en la línea de comandos:  

### ifconfig | grep "inet addr" ###


### Resultados propuestos ###

### Proyecto De Acceso Codificado ###

Desarrollar un mecanismo de acceso que permita el ingreso al personal autorizado al invernadero por medio de un contraseña  de 4 dígitos

### Proyecto Monitoreo Ambiente En Aplicaciones Web ###
     
Generar una interfaz web para monitorizar los distintos factores climáticos desde un  ordenador o dispositivo móvil que permita el cultivador mayores garantías en cuanto al cuidado y producción del cultivo.

### Proyecto Energía ###
La idea es mantener la mejor alineación posible entre el panel solar (celula fotovoltaica) y la dirección en que viaja la radiación del sol, de esta manera se logra generar la mayor cantidad de energía eléctrica la cual se almacenara en una batería, esta batería en horas de la noche alimentara el cableado eléctrico de focos, iluminando el lugar.



### Historial de versiones ###

1,0 Liberado en Octubre del 2014


### Información de contacto ###

* Desarrollador: Diego Javier Mena Amado  
Est. Ingenieria Electrónica de la Universidad Distrital FJC  
Movil: 3133067541  
Facebook: Diego Javier Brown   
Twitter: @ DiegoJavierMena  
Linkedin: Diego Javier Mena Amado  

* Desarrollador: Ivan Camilo Ruiz Mongui    
Est. Ingenieria Electrónica de la Universidad Distrital FJC  
Movil: 3209025813  
Facebook:  Ivan Camilo Ruiz  


