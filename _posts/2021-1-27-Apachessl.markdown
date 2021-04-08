---
img:logo-apache.png
typora-copy-images-to: ../miss-assets/img/apachessl/
typora-root-url: ../
layout: post
title:  "Apache SSL"
date:   2021-01-27 13:32:20 +0300
categories: jekyll update
---

## P1 Apache

## Instalación de un certificado digital en Apache

En esta guía, cubriremos cómo crear un **certificado SSL auto-firmado** para Apache en un servidor Linux, que nos permitirá cifrar el tráfico a nuestro servidor. Si bien esto no proporciona el beneficio de la  validación por parte de terceros de la identidad del servidor, cumple  los requisitos de aquellos que simplemente quieren transferir  información de forma segura.

1.Activar modulo ssl y reiniciar el servicio:

![image-20210127163013013](/miss-assets/img/apachessl/image-20210127163013013.png)

2.Crear un certificado ssl auto-firmado:

![image-20210127163111420](/miss-assets/img/apachessl/image-20210127163111420.png)

3.Configurar apache para que use ssl:

![image-20210127163214924](/miss-assets/img/apachessl/image-20210127163214924.png)

4.Configurar /etc/hosts/:

![image-20210127163301834](/miss-assets/img/apachessl/image-20210127163301834.png)

5.Activar el host virtual con ssl:

![file:///home/usuari2/Im%C3%A1genes/Captura%20de%20pantalla%202021-01-27%2016:44:09.png](/miss-assets/img/apachessl/Captura de pantalla 2021-01-27 164409.png)



6.Probar configuración:

![file:///home/usuari2/Im%C3%A1genes/Captura%20de%20pantalla%202021-01-27%2016:41:41.png](/miss-assets/img/apachessl/Captura de pantalla 2021-01-27 164141.png)

![file:///home/usuari2/Im%C3%A1genes/Captura%20de%20pantalla%202021-01-27%2016:42:32.png](/miss-assets/img/apachessl/Captura de pantalla 2021-01-27 164232.png)



7.Redirigir trafico no seguro a la https:



![file:///home/usuari2/Im%C3%A1genes/Captura%20de%20pantalla%202021-01-27%2016:40:07.png](/miss-assets/img/apachessl/Captura de pantalla 2021-01-27 164007-1611762428739.png)









