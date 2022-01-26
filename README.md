# Ejecutar-programas-de-Java-en-Consola

TEMA DEL REPOSITORIO
--------------------------------------------------------------------------------------------------------------------------------------------------------
Ejecutar programas de Java en Consola (Windows o Mac/Linux)

DESCRIPCIÓN
--------------------------------------------------------------------------------------------------------------------------------------------------------
En este repositorio se pretende hablar acerca de la ejecución de programas ````.java```` en Consola, tanto para Windows o Mac/Linux.

Aunque tenemos IDE's los cuales con un botón se compila y ejecuta un programa (de cualquier lenguaje) hay formas de compilar y ejecutar programas en Java desde la consola. Este repositorio nace por mi experiencia en la materia de Programación Orientada a Objetos, debido a que los códigos de mis prácticas (las cuales ya subi) eran ejecutadas en una página con datos de entrada predeterminados (que son los archivos de texto que vienen incluidos en casi todos los repositorios de las prácticas), por lo que para no tener que subir el código a cada rato, compilaba los programas y por medio de la consola los ejecutaba con los ````.txt```` para probarlos.

Para poder compilar un programa de Java se utiliza el siguiente comando (Windows, Mac y Linux):

````
javac main.java
````

En caso de que sean más archivos:

````
javac *.java
````

IMPORTANTE: Al ejecutarse el comando anterior se crean los ````.class```` de cada clase de los ````.java```` que se hayan compilado

Para ejecutar un programa (Windows, Mac y Linux):

````
java main
````

IMPORTANTE: El archivo qque se manda a ejecutar en el comando anterior es el ````.class```` de la clase principal. Se omite su extensión

En caso de que tengamos archivos de texto para probar los programas (como en los repositorios de las prácticas), el comando es el siguiente (Windows, Mac y Linux):

````
java main < archivoTexto.txt
````

El nombre del archivo de texto debe estár acompañado por su extensión, que es ````.txt````

NOTAS
--------------------------------------------------------------------------------------------------------------------------------------------------------
El uso de archivos de texto es para sustituir la entrada de datos del usuario (por medio del teclado). En otras palabras, evitamos tener que escribir los mismos datos para probar los programas, bastará con escribirlos en un archivo de texto. 
