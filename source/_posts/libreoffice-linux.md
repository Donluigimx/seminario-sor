---
title: Instalando LibreOffice en Linux
date: 2017-08-23 14:50:39
tags:
thumbnail: /media/img/libreoffice.png
---

## Características

LibreOffice es un paquete de software de oficina libre y de código abierto desarrollado por The Document Foundation. Se creó como bifurcación de OpenOffice en 2010. El entorno está programado en los lenguajes informáticos Java, C++ y Python.

Cuenta con un procesador de texto (Writer), un editor de hojas de cálculo (Calc), un gestor de presentaciones (Impress), un gestor de bases de datos (Base), un editor de gráficos vectoriales (Draw) y un editor de fórmulas matemáticas (Math).

Está diseñada para ser compatible con los principales paquetes ofimáticos, incluyendo Microsoft Office, aunque algunas características de diseño y atributos de formato son manejados de forma diferente o no son compatibles. LibreOffice está disponible en más de 120 idiomas (incluyendo español, catalán, vasco y gallego6) y para diferentes sistemas operativos,​ incluyendo Microsoft Windows, Mac OS X 10.4 Tiger o superior y GNU/Linux (incluyendo un visor de LibreOffice para Android​), así como en forma de una suite de oficina en línea. Es la suite ofimática por defecto en las distribuciones Linux más populares.

Entre enero de 2011 (la primera versión estable) y octubre de 2011, LibreOffice fue descargada aproximadamente 7,5 millones de veces. Desde mayo de 2011 hasta mayo de 2015, fue descargada 120 millones de veces, excluyendo las distribuciones de Linux, que desde mayo de 2014 hasta mayo de 2015 fueron 55 millones de veces descargadas.

## Instalación

### Requerimientos

- La computadora debe tener por lo menos 10 GB de almacenamiento libres.
- 2GB de Memoria RAM cómo mínimo
- Video integrado

### Actualizando repositorios

Primero, el sistema linux deberá de actualizar el listado de paquetes que tiene guardado en la computadora, esto para poder descargar las últimas versiones y obtener nuevo software listado en los servidores a donde se tiene apuntado el manejador de paquetes.

![Update](/media/img/Screenshot from 2017-08-23 15-01-53.png)

Con los repositorios actualizados, es momento de actualizar el sistema linux.

![Upgrade](/media/img/Screenshot from 2017-08-23 15-05-31.png)

### Libreoffice

Dentro de la terminal, se tecleará el siguiente comando:

```bash
sudo apt-get install libreoffice
```

![install](/media/img/Screenshot from 2017-08-23 15-08-24.png)
Este comando instalará toda la librería de office.
![installed](/media/img/Screenshot from 2017-08-23 15-08-11.png)

### Diferencias entre Microsoft Office

En el aspecto visual es donde se notará más la diferencia entre estos dos, ya que Microsoft Office cuida demasiado este punto. La intuitividad que tiene Microsoft Office y lo fácil que es utilizarlo es muy difícil de imitar, ya que Libreoffice tiene una complejidad absurda.

Los dos pueden tener distintas fuentes ya sea para excel, writer o algún otro miembro de la paquetería.

La edición de imagenes dentro de Libreoffice es muy tosca y poca simple de utilzar. Los margenes y demás son difíciles de aplicar.

Libreoffice tiene una ventaja importante en donde se pueden realizar plugins para cualquier software de la paquetería, programada, ya sea en Java o en Python, agregando funcionalidades extras que no se pueden obtener ni en Microsoft Office.

Lo último y más importante: Libreoffice cuesta $0 mientras que Microsoft Office, su versión más básica cuesta $1500.
