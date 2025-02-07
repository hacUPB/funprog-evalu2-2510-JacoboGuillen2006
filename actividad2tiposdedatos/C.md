En el lenguaje de programación C, los tipos de datos constituyen la semántica y las características del almacenamiento de elementos de datos. Se expresan en la sintaxis del lenguaje en forma de declaraciones de ubicaciones de memoria o variables. Los tipos de datos también determinan los tipos de operaciones o métodos de procesamiento de elementos de datos.

El lenguaje C proporciona tipos aritméticos básicos, como tipos de números enteros y reales, y sintaxis para crear tipos de matrices y compuestos. Los encabezados de la biblioteca estándar C, que se utilizarán mediante directivas de inclusión, contienen definiciones de tipos de soporte que tienen propiedades adicionales, como proporcionar almacenamiento con un tamaño exacto, independientemente de la implementación del lenguaje en plataformas de hardware específicas. 

El lenguaje C proporciona los cuatro especificadores de tipos aritméticos básicos char, int, float y double, y los modificadores signed, unsigned, corto y largo

Char: el tipo de dato char es un tipo entero de 8 bits de longitud. Sin embargo, tiene un alcance un poco más allá de ser un entero

En C podemos representar un caracter con el tipo char. Estos son llamados también character literals.

char option = 'N';

Sin embargo, un char es en esencia un tipo entero que puede guardar números en un rango desde -127 hasta 128.

int: El tipo int se utiliza para representar números enteros de 32 bits de longitud (en  compiladores antiguos podrían ser 16 bits). Podemos declarar enteros usando la palabra reservada int seguido del nombre de la variable o variables que deseamos declarar.

int a;

int a, b;

Podemos inicializar las variables anteriores de la siguiente forma:

a = 2353;
b = -14564;

Se puede asignar a un tipo entero un valor decimal, hexadecimal u octal. En el siguiente ejemplo se declaran e inicializan diferentes variables con el mismo valor en sus distintas representaciones

int a = 58;
int b = 072;  // octal
int c = 0x3A; // hexadecimal

Float: El tipo float se utiliza para representar un dato en coma flotante de 32 bits de longitud en el formato IEEE 754 (esto es un bit para el signo, 8 bits para el exponente y 23 para la mantisa). Este tipo de dato almacena valores con una precisión aproximada de siete dígitos. Podemos declarar enteros usando las palabras reservada float seguido del nombre de la variable o variables que deseamos declarar.

float a = 8.2345F;
float b = 2.2e-5F; /* notación exponencial */

Double: El tipo double se utiliza para representar un dato en coma flotante de 64 bits de longitud en el formato IEEE 754 (esto es un bit para el signo, 11 bits para el exponente y 52 para la mantisa). Este tipo de dato almacena valores con una precisión aproximada de 16 dígitos. Podemos declarar enteros usando las palabras reservada double seguido del nombre de la variable o variables que deseamos declarar.

float a = 8.2345;
float b = 2.2e-5; /* notación exponencial */



