al ejecutar el programa (explicado mas a delante)

te ofrecera 5 maneras para analizar el texto*, para ello precionas 1, 2, 3, 4, 5 o 6 y luego enter. 

   1) statsWords.sh: Indicador estadístico de longitud de palabras (la más corta, la más larga y el promedio de longitud).

   2) statsUsageWords.sh: Indicador estadístico de uso de palabras, deben ser de al menos 4(cuatro) letras. (mostrar un Top Ten de estas palabras ordenadas desde la que tiene más apariciones a la que tiene menos). Es decir, filtrar las palabras que tengan al menos 4 letras y de éstas, elegir las 10 más usadas.

    3) findNames.sh: Identificación de nombres propios (se identifican sólo si están en este formato Nnnnnnnnn), aunque la palabra no sea un nombre propio realmente. Ejemplos: Mateo, Estonoesunnombre, Ana.

    4) statsSentences.sh: Indicador estadístico de longitud de oraciones (la más corta, la más larga y el promedio de longitud).

    5) blankLinesCounter.sh: Contador de líneas en blanco.

    6) Salir: cierra el programa 

Para ejecutar el docker (una vez instalado y configurado git o usando la app del mismo), lo primero que se deben ejecutar los siguientes comandos
	$ git clone https://github.com/JoanRoland/EntornoDProgramacion
	$ cd EntornoDProgramacion 
	$ sudo docker build --tag tpfinal:1.0 .
	$ sudo docker run -it --rm tpfinal:1.0

* le texto de ejemplo es una hoja del libro Camino de los Reyes de la saga del Archivo de las tormentas 
        

