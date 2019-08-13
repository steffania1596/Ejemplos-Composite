# Patrón estructural Composite
#Componentes:
El patron de diseño Composite tiene como principales componentes: 

-Componente: interfaz o clase abstracta. Tiene operaciones mínimas(Gráfico de vectores).

-Hoja: Objeto primitivo, extiende o implementa del componente (Una línea).

-Composite: Componente que tiene hijos, que pueden ser composite o Hoja. (Triángulo dibujado con 3 líneas). 

-Cliente: Código que manipula y usa objetos de tipo hoja o composición a través de su interfaz pública <<Componente>> (Cliente llama método dibujar). 
  
   ![alt text](https://oscarblancarteblog.com/wp-content/uploads/2014/10/composite.png) 

#Proposito:
-El Composite provee a los clientes un mismo trato para todos los objetos que forman la jerarquía. 

-Cada elemento del nodo es capaz de ejecutar una operación que se encargará de iterar sobre todos los subelementos que contiene, ejecutando la operación de cada uno de ellos.

 -Controles de formulario, donde los objetos (botones, literales, paneles,..), heredan de la clase Control. Los cuales a su vez contienen una colección de otros objetos que heredan de la clase Control. (Se pueden tratar como control individual o como colección de controles).

-Sistema de pipeline de petición/respuesta ASP.NET.

Estructura de ficheros y directorios de un sistema de archivos. 
 
