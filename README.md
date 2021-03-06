# Informe-Laboratorio-3
## 1. OBJETIVOS

   1.1 GENERAL
   
Analizar el manejo correcto de los nodos en los circuitos eléctricos expuestos, a través de la elaboración del Laboratorio N°3 se va hacer uso de las leyes fundamentales antes estudiadas y de esta forma mejorar la comprensión sobre el comportamiento que existe dentro de un circuito.

   1.2 ESPECÍFICOS
   
* Encontrar el voltaje en el circuito eléctrico aplicando el análisis de nodos.
* Determinar la diferencia que existe entres los resultados de analíticos,experimentales y simulados.
* Aplicar la ley de Kirchhoff para cada uno de los nodos que no son de referencia posteriormente hacer uso de la ley de Ohm para expresar las corrientes de las ramas en términos de los voltajes de nodo.

## 2. MARCO TEÓRICO

En un circuito eléctrico, un nodo es un punto donde se cruzan dos o más elementos de circuitos, sea una fuente de voltaje o corriente, resistencias, capacitores, inductores, etc.

![image](https://user-images.githubusercontent.com/93666408/143991305-4b8bb10d-d377-4680-966e-5aee1c8d5f7f.png)

El análisis de nodos nos ofrece tres criterios importantes que son los siguientes:
1) Nos proporciona modos diferentes de transformar diagramas de circuitos en matrices con un número mínimo de incógnitas.
2) Las ecuaciones planteadas de forma matricial se deben dar en forma estándar pero su solución debe ser en forma manual  o por computadora.
3) Cualquiera o todas las demás variables de interés, se deben obtener a partir de la solución de la ecuación matricial.


Para este método, interesa hallar los voltajes de nodo. La ventaja de aplicar este método es el número de incógnitas, a diferencia de usar los métodos convencionales, el análisis se volvería complejo con altas probabilidades de cometer errores.
Citando al texto de fundamentos de circuitos eléctricos, el análisis de nodos nos brinda un procedimiento general para resolver circuitos con el uso de voltajes de nodo como variables a encontrar.
La elección de los voltajes de nodo en vez de voltajes de elementos o dispositivos, resulta conveniente y reduce la cantidad de ecuaciones simultáneas a resolver.

![image](https://user-images.githubusercontent.com/93666408/143992215-181caed5-835f-448d-a66b-ca597e7b920c.png)
![Untitled (1)](https://user-images.githubusercontent.com/93666408/143994101-800c6913-bcd6-4668-82e8-36974991e4cc.jpg)



## 3. EXPLICACIÓN DEL PROCEDIMIENTO

En primer lugar identificamos nuestro circuito y procedemos a localizar nuestros nodos principales y de referencia.
* Circuito
![Circuito](https://user-images.githubusercontent.com/93681159/143967999-09a38dd4-c952-4f5f-9b72-416e717354ce.jpeg)
* Nodos principales
![Nodos](https://user-images.githubusercontent.com/93681159/143968008-051fd986-8f34-4872-89b0-67ef7e478290.jpg)
* Nodo de referencia
![Nodo_ref](https://user-images.githubusercontent.com/93681159/143967680-d28ee2a0-cc8d-4786-97a0-2ab62bf4852d.jpg)

Una vez identificados los nodos principales y nuestro nodo de referencia procedemos a identificar la dirección de nuestras corrientes y realizar su respectivo análisis.
* Direcciones
![Direcciones](https://user-images.githubusercontent.com/93681159/143970057-3ef0e2df-47ff-472e-a58d-30b68e61301d.jpeg)
* Nodo A
![Nodo A](https://user-images.githubusercontent.com/93681159/143970065-f176e92c-4687-4eab-9a77-0061a6f854f4.jpeg)
* Nodo B
![Nodo B](https://user-images.githubusercontent.com/93681159/143970620-06a40065-1960-4cea-afe7-67be7ae7125f.jpeg)

Luego de haber realizado el análisis de los nodos, obtenemos un sistema de dos ecuaciones con dos incógnitas el cual resolveremos mediante una calculadora online.
![image](https://user-images.githubusercontent.com/93681159/143970931-ed5c5e60-69fe-4414-8938-46785cb21bb8.png)
![image](https://user-images.githubusercontent.com/93681159/143970964-4904ed0d-1e41-4bf5-bc55-d6d640667e04.png)
![Respuestas](https://user-images.githubusercontent.com/93681159/143971447-fa33f8bf-2f7e-4e7c-8d64-2a4bc0ca2fbd.jpeg)
#### Resultados simulados
![image](https://user-images.githubusercontent.com/93681159/143973341-20610dca-dd65-491a-8022-284d75d401b6.png)
#### Resultados Experimentales
![image](https://user-images.githubusercontent.com/93681159/144061129-a1bd9b83-30aa-4deb-a07f-be0be40039a4.png)
#### Tabla de resultados
| NODO | Resultados Analíticos | Resultados Experimentales | Resultados Simulados |
| ------------- | ------------- | ------------- | ------------- |
|  A  |  2.82028 V  |  2.82 V  |  2.82 V  |
|  B  |  4.80195 V  |  4.80 V  |  4.80 V  |
## 4. VIDEO
https://www.youtube.com/watch?v=F7fcEanEuoA&t=1s

## 5. CONCLUSIONES
* Es importante cumplir con un orden establecido para el análisis de nodos,ya que si no se cumple con la organización adecuada se puede cometer errores en el momento de realizar los calculos pertinentes.
* Como dato adicional las leyes de Kirchhoff cumplen con un rol importante dentro del análisis,nos facilitaron el cálculo de mallas y nodos en el circuito,y que el margen de error que presenta sea debido a las resistencias que componen el circuito.
* Por último en el presente informe se llego a la conclusión sobre la importancia de analizar los nodos en un circuito eléctrico es que cuando al analizar el nodo de referencia que el valor del voltaje es cero, también saber los voltajes que regulan cada una de las resistencias de un circuito y la corriente que entra tiene que ser igual a la corriente que salen en todo el circuito y establecer el sentido de las corrientes en los nodos.
## 6. BIBLIOGRAFÍA 
* Floyd, T. (2007). Principios de circuitos electricos (Octava edi). México: Pearson
* Anónimo. (s/f). Sistema de tres ecuaciones lineales con tres incógnitas. Calculadora online. http://matematicas.relatividad.org/widget-sistema-tres-incognitas.html
