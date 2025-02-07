En Python, todo valor que pueda ser asignado a una variable tiene asociado un tipo de dato. Así que los tipos de datos serían las clases (donde se definen las propiedades y qué se puede hacer con ellas) y las variables serían las instancias (objetos) de los tipos de datos.

Los tipos de datos básicos de Python son los booleanos, los numéricos (enteros, punto flotante y complejos) y las cadenas de caracteres.

Tipos numéricos: Python define tres tipos de datos numéricos básicos: enteros, números de punto flotante (simularía el conjunto de los números reales, pero ya veremos que no es así del todo) y los números complejos.

Números enteros
El tipo de los números enteros es int. Este tipo de dato comprende el conjunto de todos los números enteros, pero como dicho conjunto es infinito, en Python el conjunto está limitado realmente por la capacidad de la memoria disponible. No hay un límite de representación impuesto por el lenguaje.

Números complejos
El último tipo de dato numérico básico que tiene Python es el de los números complejos, complex.
Los números complejos tienen una parte real y otra imaginaria y cada una de ellas se representa como un float.
Para crear un número complejo, se sigue la siguiente estructura <parte_real>+<parte_imaginaria>j. Y se puede acceder a la parte real e imaginaria a través de los atributos real e imag:

Tipo booleano
En Python la clase que representa los valores booleanos es bool. Esta clase solo se puede instanciar con dos valores/objetos: True para representar verdadero y False para representar falso.
Una particularidad del lenguaje es que cualquier objeto puede ser usado en un contexto donde se requiera comprobar si algo es verdadero o falso. Por tanto, cualquier objeto se puede usar en la condición de un if o un while (son estructuras de control que veremos en tutoriales posteriores) o como operando de una operación booleana.