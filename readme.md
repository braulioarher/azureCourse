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