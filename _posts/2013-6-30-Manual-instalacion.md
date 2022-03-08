---
layout: post
title: Manual de instalación
---
Para configurar o entorno de produción necesitaremos instalar previamente as seguintes ferramentas:

* PostgreSQL 8.4
* PostGis 1.5 (tutorial de configuración) 
* Apache Tomcat 7.0 e configurado para CGI-BIN. (Teña en conta esta informacion destas ligazóns, Ligazón 1, Ligazón 2. 


**1)Instalación da base de datos** Copias o ficheiro copia_bd.sql . Restauras este ficheiro no PosgtreSQL 8.4 e terás unhas base de datos chamada xeoPesca, está contén datos de exemplo iniciais. 

**2) Instalación de GeoServer 2.3.0** Terás que instalar e despregar o GeoServer 2.3.0 no servidor Tomcat no directorio /webapps/geoserver. Unha vez instalado GeoServer deberás crear unha nova capa chamada “vista_faena_lance” que faga referencia a vista a vista faena. 

**3) Despregar xeoPesca** Descargaste o war e  o despregas. O proxecto xeopesca debese despregar no  ROOT do Tomcat. Configuración dos ficheiros de acceso a base de datos:

 - Configuración de Hibernate Spatial No arquivo /src/main/resources/META-IF/persistence.xml
- Configuración da base de datos para Spring. No arquivo /src/main/resources/hibernate.cfg.xml Editar os parámetros de acceso a base de datos polos os da túa instalación.


**Unha vez realizado isto só che queda arrincar o Tomcat.**

Para configurar el  entorno de producción necesitamos instalar previamente las siguientes herramientas:

- PostgreSQL 8.4
- PostGis 1.5 (tutorial de configuración) 
- Apache Tomcat 7.0 e configurado para CGI-BIN. (Tenga en cuenta esta notas, [Enlace1](http://lekshmideepu.blogspot.com/2013/03/configure-tomcat-7-to-run-python-cgi.html), [Enlace 2](https://codigoaldescubierto.wordpress.com/2008/02/24/cgis-en-tomcat-bajo-windows/). 


1)Instalación da base de datos Copias el ficheiro copia_bd.sql . Restauras este ficheiro en el PosgtreSQL 8.4 y tendrás una  base de datos llanada xeoPesca, está contiene datos de ejemplo iniciales. 2) Instalación de GeoServer 2.3.0 Terás que instalar e despregar o GeoServer 2.3.0 no servidor Tomcat no directorio /webapps/geoserver. Unha vez instalado GeoServer deberás crear unha nova capa chamada “vista_faena_lance” que faga referencia a vista a vista faena. 3) Despregar xeoPesca Descargaste o war e  o despregas. O proxecto xeopesca debese despregar no  ROOT do Tomcat. Configuración dos ficheiros de acceso a base de datos:

 Configuración de Hibernate Spatial No arquivo /src/main/resources/META-IF/persistence.xml
Configuración da base de datos para Spring. No arquivo /src/main/resources/hibernate.cfg.xml Editar os parámetros de acceso a base de datos polos os da túa instalación.


**Unha vez realizado isto só che queda arrincar o Tomcat.**

Para configurar o entorno de produción necesitaremos instalar previamente as seguintes ferramentas:

PostgreSQL 8.4
PostGis 1.5 (tutorial de configuración) 
Apache Tomcat 7.0 e configurado para CGI-BIN. (Teña en conta esta informacion destas ligazóns, Ligazón 1, Ligazón 2. 

1)Instalación da base de datos Copias o ficheiro copia_bd.sql . Restauras este ficheiro no PosgtreSQL 8.4 e terás unhas base de datos chamada xeoPesca, está contén datos de exemplo iniciais. 2) Instalación de GeoServer 2.3.0 Terás que instalar e despregar o GeoServer 2.3.0 no servidor Tomcat no directorio /webapps/geoserver. Unha vez instalado GeoServer deberás crear unha nova capa chamada “vista_faena_lance” que faga referencia a vista a vista faena. 3) Despregar xeoPesca Descargaste o war e  o despregas. O proxecto xeopesca debese despregar no  ROOT do Tomcat. Configuración dos ficheiros de acceso a base de datos:

 Configuración de Hibernate Spatial No arquivo /src/main/resources/META-IF/persistence.xml
Configuración da base de datos para Spring. No arquivo /src/main/resources/hibernate.cfg.xml Editar os parámetros de acceso a base de datos polos os da túa instalación.
Unha vez realizado isto só che queda arrincar o Tomcat.