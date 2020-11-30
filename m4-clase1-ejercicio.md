# Modelos de Datos - Ejercicio

En este ejercicio abordaremos una problemática usual en el mundo del desarrollo, comprendiendo la lógica de negocio y realizando el modelamiento de datos para implementar una base de datos. Ésta será tal que pueda utilizarse para la implementación de un software de apoyo a la operación del negocio.  

Resolveremos este problema en 3 Etapas. 

## Etapa 1  

Usted debe crear una hoja de cálculo como un favor para un grupo de amigos que poseen una empresa pequeña. Esta empresa fabrica diversos artículos de cuero. El precio de cada artículo depende de:  
1. Los costos unitarios de la materia prima (Principalmente cuero) utilizada para la fabricación.  
2. El tiempo y esfuerzo invertidos en el proceso.   

La empresa compre cuero en lotes que poseen precios distindos dependiendo de la calidad de éstos. Adicionalmente, dada las variaciones en la disponibilidad de las materias primas en el mercado, el precio de éstas varían según la fecha en que se realizan las compras.  

Las existencias en bodega son utilizadas de acuerdo a lo requerido por las órdenes de compra que la empresa recibe de sus clientes.  

Cada lote de cuero en sus existencias provee material para múltiples productos vendidos a sus clientes.  

Se nos ha encomendado la tarea de crear una hoja de cálculo que permita visibilizar lo siguiente:  

1. Valor actualizado del total de activos (Materias primas y productos en existencia).  
2. Lotes de cuero en stock, clasificados según calidad.  
3. Precio y calidad del cuero utilizado para cada producto fabricado.  
4. Resumen de órdenes de compra recibidas desde distintos clientes, con su correspondiente listado de productos, cantidades, precios y fechas.  

Cree un repositorio GitHub de su archivo y ubíquelo en un directorio doc/ dentro del directorio principal del proyecto.  

## Etapa 2  

Se solicita modelar el escenario analizado en la **Etapa 1**, utilizando un diagrama ER. Al final de el presente documento, se entrega un listado de los elementos estándar para la confección del diagrama.  

Se sugiere utilizar la [Aplicación **Diagrams.Net**](https://www.diagrams.net/) para dibujar su diagrama.  

Debe justificar la eleccion de tipos de entidades, atributos, relaciones y conectores.  

Suba los archivos: fuente `xml` y el renderizado `PDF` de su diagrama. Éstos deben estar ubicados en el directorio `doc/` creado en el repositorio GitHub de la **Etapa 1**.  

## Etapa 3  

A partir de los resultados de la **Etapa 2**:  

1. Elabore un modelo relacional, asignando atributos, tipos de datos (justifique sus elecciones) y llaves. En esta etapa es posible y aceptable que usted decida actualizar el diagrama de la **Etapa 2**. Se sugiere utilizar la [Aplicación **Diagrams.Net**](https://www.diagrams.net/) para dibujar su diagrama.    

2. Aplique las reglas de normalizacion a su modelo relacional, debe entregar un modelo que esté en **3ra Forma Normal**.  

3. Escriba pequeños scripts intuitivos en base a sentencias SQL para llenar las tablas y establecer las relaciones.  


## ANEXO: Símbolos Diagramas ER    

![](simbolos-ER.png)    
