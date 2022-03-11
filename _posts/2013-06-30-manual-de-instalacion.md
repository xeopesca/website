---
title: "Manual de instalación"
date: "2013-06-30"
categories: 
  - "novas"
---

(en) Para configurar o entorno de produción necesitaremos instalar previamente as seguintes ferramentas:

- PostgreSQL 8.4
- PostGis 1.5 ([tutorial de configuración](http://proyectosbeta.blogspot.com.es/2012/03/instalar-postgres-postgis-en-debian.html)) 
- Apache Tomcat 7.0 e configurado para CGI-BIN. (Teña en conta esta informacion destas ligazóns, [Ligazón 1](http://lekshmideepu.blogspot.com.es/2013/03/configure-tomcat-7-to-run-python-cgi.html), [Ligazón 2](http://codigoaldescubierto.wordpress.com/2008/02/24/cgis-en-tomcat-bajo-windows/). 

**1)Instalación da base de datos** Copias o ficheiro [copia\_bd.sql](http://xeopesca.com/install/copia_bd.sql) . Restauras este ficheiro no PosgtreSQL 8.4 e terás unhas base de datos chamada xeoPesca, está contén datos de exemplo iniciais. **2) Instalación de GeoServer 2.3.0** Terás que instalar e despregar o GeoServer 2.3.0 no servidor Tomcat no directorio /webapps/geoserver. Unha vez instalado GeoServer deberás crear unha nova capa chamada “vista\_faena\_lance” que faga referencia a vista a vista faena. **3) Despregar xeoPesca** [Descargaste o war](http://xeopesca.com/install/webapp.war) e  o despregas. O proxecto xeopesca debese despregar no  ROOT do Tomcat. Configuración dos ficheiros de acceso a base de datos:

-  Configuración de Hibernate Spatial No arquivo /src/main/resources/META-IF/persistence.xml
- Configuración da base de datos para Spring. No arquivo /src/main/resources/hibernate.cfg.xml Editar os parámetros de acceso a base de datos polos os da túa instalación.

**Unha vez realizado isto só che queda arrincar o Tomcat.**

Para configurar el  entorno de producción necesitamos instalar previamente las siguientes herramientas:

- PostgreSQL 8.4
- PostGis 1.5 ([tutorial de configuración](http://proyectosbeta.blogspot.com.es/2012/03/instalar-postgres-postgis-en-debian.html)) 
- Apache Tomcat 7.0 e configurado para CGI-BIN. (Tenga en cuenta esta notas, [Enlace1](http://lekshmideepu.blogspot.com.es/2013/03/configure-tomcat-7-to-run-python-cgi.html), [Enlace 2](http://codigoaldescubierto.wordpress.com/2008/02/24/cgis-en-tomcat-bajo-windows/). 

**1)Instalación da base de datos** Copias el ficheiro [copia\_bd.sql](http://xeopesca.com/install/copia_bd.sql) . Restauras este ficheiro en el PosgtreSQL 8.4 y tendrás una  base de datos llanada xeoPesca, está contiene datos de ejemplo iniciales. **2) Instalación de GeoServer 2.3.0** Terás que instalar e despregar o GeoServer 2.3.0 no servidor Tomcat no directorio /webapps/geoserver. Unha vez instalado GeoServer deberás crear unha nova capa chamada “vista\_faena\_lance” que faga referencia a vista a vista faena. **3) Despregar xeoPesca** [Descargaste o war](http://xeopesca.com/install/webapp.war) e  o despregas. O proxecto xeopesca debese despregar no  ROOT do Tomcat. Configuración dos ficheiros de acceso a base de datos:

-  Configuración de Hibernate Spatial No arquivo /src/main/resources/META-IF/persistence.xml
- Configuración da base de datos para Spring. No arquivo /src/main/resources/hibernate.cfg.xml Editar os parámetros de acceso a base de datos polos os da túa instalación.

**Unha vez realizado isto só che queda arrincar o Tomcat.**

Para configurar o entorno de produción necesitaremos instalar previamente as seguintes ferramentas:

- PostgreSQL 8.4
- PostGis 1.5 ([tutorial de configuración](http://proyectosbeta.blogspot.com.es/2012/03/instalar-postgres-postgis-en-debian.html)) 
- Apache Tomcat 7.0 e configurado para CGI-BIN. (Teña en conta esta informacion destas ligazóns, [Ligazón 1](http://lekshmideepu.blogspot.com.es/2013/03/configure-tomcat-7-to-run-python-cgi.html), [Ligazón 2](http://codigoaldescubierto.wordpress.com/2008/02/24/cgis-en-tomcat-bajo-windows/). 

**1)Instalación da base de datos** Copias o ficheiro [copia\_bd.sql](http://xeopesca.com/install/copia_bd.sql) . Restauras este ficheiro no PosgtreSQL 8.4 e terás unhas base de datos chamada xeoPesca, está contén datos de exemplo iniciais. **2) Instalación de GeoServer 2.3.0** Terás que instalar e despregar o GeoServer 2.3.0 no servidor Tomcat no directorio /webapps/geoserver. Unha vez instalado GeoServer deberás crear unha nova capa chamada “vista\_faena\_lance” que faga referencia a vista a vista faena. **3) Despregar xeoPesca** [Descargaste o war](http://xeopesca.com/install/webapp.war) e  o despregas. O proxecto xeopesca debese despregar no  ROOT do Tomcat. Configuración dos ficheiros de acceso a base de datos:

-  Configuración de Hibernate Spatial No arquivo /src/main/resources/META-IF/persistence.xml
- Configuración da base de datos para Spring. No arquivo /src/main/resources/hibernate.cfg.xml Editar os parámetros de acceso a base de datos polos os da túa instalación.

**Unha vez realizado isto só che queda arrincar o Tomcat.**
