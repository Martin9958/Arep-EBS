# Taller de Patrones de Arquitectura ESB

## Introduccion
En este taller se aprenderá a instalar y manipular un ESB. Al final del taller debe subir un artículo detallando la arquitectura de ServiceMix y de la solución desarrollada (Trabajo individual).
Para el taller usted debe seguir los pasos siguientes:
- Instale ServiceMix y siga los pasos descritos en el Link a continuación http://servicemix.apache.org/docs/7.x/quickstart/index.html
- Ahora vamos crear un cliente externo que se conecte al Bus que acaba de instalar. Concretamente nos vamos a conectar a la cola events en ActiveMQ.
- Cree un proyecto maven de java.
- Agregue una dependencia en el pom para traer las librerías necesarias para conectarse
```
<dependencies>
  <!-- https://mvnrepository.com/artifact/org.apache.activemq/activemq-camel -->
  <dependency>
    <groupId>org.apache.activemq</groupId>
    <artifactId>activemq-camel</artifactId>
    <version>5.14.4</version>
  </dependency>
 </dependencies>
```
- Ahora implemente el cliente
- Configure ServiceMix con una ruta que pase los mensajes de la cola events a la cola salida.
- Cree un cliente que lea los mensajes de esta cola y los imprima en pantalla. Modifique el código a continuación, ojo mire el código anterior para ver la configuración de seguridad
- Instale service mix en AWS, y conéctese usando el cliente.
- Construya un artículo corto ( 4 páginas) con la Arquitectura de Service Mix y la arquitectura del ejemplo que acaba de desarrollar.

## Arquitectura de ServiceMix 

## Arquitectura Implementada

## Imagenes del Resultado

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A1.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A2.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A3.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A4.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A5.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A6.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A7.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A8.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A9.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A10.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A11.PNG)

![](https://github.com/Martin9958/Arep-EBS/blob/master/imagenes/A12.PNG)

