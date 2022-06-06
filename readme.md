# Curso de azure de inovacion virtual

El objetivo de este curso es conocer los servicios de Microsoft Azure.

## Aspectos basicos de Azure

En este modulo se repasa o se introduce que es o que son los servicios de la nube y la nube. Se marca cuales son las categorias o bloques generales de los servicion un ejemplo seria servicios de IoT, Servicios de almacenamiento y bases de datos

Se diferencia los métodos para crear una suscripcion de azure

## 2.- Conceptos Fundamentales de Azure

Existen nubes privadas, pulicas e hibrida (privada e hibrida).

En este modulo se aprendio a identificar los distintos modelos de la nueve que existen como los son privada, publica e hibrida, tambien se identificaron las ventajes de usar los servicios en la nube como ejemplo la escalabilidad, fiabilidad, fexibilidad y geolocalizacion. Dentro de los servicios de la nube existen diferentes categorias como lo son Iaas (Infrestructure as Service), Plataform as Service (Paas) y Software as Service (Saas) cada una con sus particularidades que el uso va depender del prodcuto que se necesite desarrollar.

## 3.- Descripcion de los componentes de la arquitectura de Azure

Los componentes mas basicos de los componentes de azure son los recursos que son equivalente a los servicios despues en la gerarquia tenemos los grupos de recursos que rsirve para ordenar los recursos dependiendo de la aplicacion, despues tenemos la suscripcion que corresponde a como se pagan los grupos de recursos y por ultimo lo grupos de administracion

Zonas de disponibilidad.

Una region de azure esta compuesta por dos o mas zonas de disponibilidad

Grupos de administracion
Suscripciones
Grupos de recursos
Recursos

En este modulo se aprendio que son las suscripciones y grupos de administracion de azure
tambien que que son los recurso de azure, los grupos de recursos y azure resource manager
asi como las regiones de azure peres de regiones y zonas de disponibilidad.

## Exploracion de servicios de azure compute

Una VM es un ambiente corriendo dentro de ambiente o una computadora corriendo dentro de otra computadora

    En una VM se tiene control total del OS
    Puede ejecutar software personalizado
    Usar configuraciones de hospedaje personalizado

### Conjuntos de escaldo de VM

    Es un grupo de VM que se puede extender o disminuir dependiendo de la necesidad

### Azure AppService

    Es un servicio que te permite alojar tu aplicacion ya sea Web, API, trabajo o movil y esta se ajusta a las necesidades, trabafico y demanda de servicios

### Azure containers

    A diferencia de las VMs los ocntenedeores no implican memoria, cpu solamente el sistema operatico OS los contenedores se pueden usar con docker

    Kubernetes es un orquestador de contenedores

    Los microservicios son operaciones que se van ejecutando segun los mande a llamar kubernetes

### Azure functions

    Son implementaciones de azure sin servidor, son funciones que se ejecutan en muy poco tiempo realiznando solamente lo que se le indica a la funcion ejemplo una funcion de consulta
    -Se escala controla por eventos
    -Se tiene una microfacturacion solo se cobra por ejecucion y por tiempo de ejecucion
    -Se usan para aplicaciones tipo REST

### Azure virtual desktop

    Es como un escritorio que todos conocemos pero esta disponible en linea y si tienes licensias de windows enterpice puedes usarlo entre y solo pagar por lo que se usa

En conclusion en esta unidad se descubrienron algunos de los servicios mas a detalle y cuando usar cada uno de ellos un ejemplo de los vistos son las VMs, los sercios de azure functions y azure appservice

## Servicios de red de azure

Toda red vitual funciona como red fisica

## VPN Gateway

Una VPN es red privada virtual que integra una parte de seguridad sirve para cifrar informacion a travez de internet de esta forma mandar por conexion segura de forma cifrada

Se usan para conectarse a redes locales solamente se manda por una vpn definida

Los tamannios de las instancias de VPN Gateway depende de la cantidad de datos que se va a enviar

## Azure ExpressRoute

Te asigna una conexion directa a azure para estar mas seguro sin pasar por internet, literalmente te conectan con cable a la red de azure

Usa una red primaria y secundaria por temas de redundancia

## Servicios de Azure Storage

### Azure Storage

Se necesita una cuenta de Azure Storage

### Disk Storage

Son los discos para las maquinas virtuales, hay de diferentes caracteristicas como SSD y HDD las maquinas virtuales pueden acceder a ellos segun su necesidad

Es completamente una Iaas "Infrestructura como servicio"

### Azure Blob Storage

Una forma de almacenamiento para objetos se puede organizar en forma de contenedores y estas puden guargar grandes cantidades de datos sirve para streaming de audio y video, analisis de datos

### Azure Files

Funciona como una carpeta compartida

### Niveles de acceso

Segun la forma y la frecuencia a la que accedamos a nuestros archivos a estos se les deben de asignar un nivel de acceso existen tres niveles:
        -   Nivel de accesso frecuente
        -   Nivel de accesso esporadico: se alamcena por al menos de 30 dias
        -   Nivel de accesso de archivo: raramente se acceden y se alamcenan por lo menos cada 180 dias

Cada nivel de acceso tiene un procesamiento diferente y una facturacion diferente.

## Practica  "Cracion de una logicApp"

Un sistema contenerizado es un conjunto de recursos que funcionanentre si

    -Se crea una logic dentro de un nuevo recurso app por cuestiones practicas

Se creo una logic app la cual responde a un trigger que se puede escoger de diferentes medios como por ejemplo Microsoft forms,
al recibir un trigger la logic app reacciona y ejecuta algo como por ejemplo enviar un correo electronicos

## Servicios de analisis y bases de datos

Azure Cosmos database es un servicio de base de datos distribuido global, un motor de base de datos que admite diversas tipo de base de datos como Maria DB, Mongo DB, etc.

Azure SQL Database es la version de Azure de SQL Server es una PaaS (Plataforma como servicio) Azure tiene un servicio de apoyo para migrar los datos de una nube local a una nube publica para hacer la migracion mas simple

Se pudo crear una base detos que contiene unas tablas de muestras se hizo una consulta donde se unen dos tablas donde el ID de un producto coicide

MySQL es otro motor de base de datos LAMP (Linux, Apache, MySQL, PHP)

PosrgreSQL es otro motor de base de datos tambien esta incluido en Azure se usa para base de datos que son muy grandes

SQL Manage Instance hace mas facil la parte de migracion tiene las mismas caracteristicas que Azure SQL. A diferencia de Azure SQL,
Azure Manage Instance ayuda mas a la parte de migracion.

Analisis y Macrodatos macrodatos se refiere a gran cantidad de datos, tiene varios servicios como los son:

    Azure Synapse Analitics: Tiene diferente fuente de datos y encapsula todas estas fuentes en dashboards para identificar patrones para su analisis.
    Azure HDInsight: Es un servicio de codigo abierto, hace mas facil la integracion con otros servicios. Permite hacer las integracion dentro de Azure
    Azure Data Lake: Prepara los datos para integrar la inteligencia artificial. Se puede hacer consulta para buscar relaciones entre datos

## Azure IoT
