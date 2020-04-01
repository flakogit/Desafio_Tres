1.- Descripci�n de la implementaci�n

Se rescatan los datos proveidos por la clase Valores y DatosUf (ambas forman parte del Jar proveido por ustedes)
Dentro de los datos obtenidos, se rescata la fecha de inicio y fecha de fin del periodo a procesar y un set con fechas y valores de uf.
Se procede a convertir el objeto Set y transformarlo en un objeto de tipo List, esto para trabajar con objetos iguales, ya que la lista que se obtiene de la clase DatosUf es de tipo List.
Luego se procede a realizar el ordenamiendo de la lista en forma descendente, seg�n las especificaciones.
Se procede a obtener los datos de la clase DatosUf, para el periodo (fecha inicio y fecha fin) que se obtuvo desde la clase Valores.
Teniendo ambas listas, se procede a realizar una comparaci�n con el fin de encontrar los datos que faltantes dentro de la lista obtenida de la clase Valores.
Una vez identificados los datos faltantes, se proceden a agregar a la lista obtenida desde la clase Valores.
Al finalizar el recorrido de ambas listas, la lista "inicial" (obtenida desde la clase Valores), se encuentra completa con los datos restantes, obtenidos de la segunda lista (lista clase DatosUf).
Se procede nuevamente a ordenar la lista "inicial" (ya completa con los valores del periodo) en forma descendente.
Luego se procede a crear una lista final s�lo con los 100 primeros registros obtenidos de la lista "inicial" (ordenados de forma descendente), para conformar el cuerpo del archivo XML de salida.
Finalmente, se procede a generar el archivo XML de salida, seg�n lo indicado en las especificaciones.

Nota: Todo lo anteriormente detallado, se encuentra comentado en el c�digo fuente.
 
2.- Tecnolog�a y librer�as utilizadas

Tecnolog�as:

Java versi�n 1.8
Springboot versi�n 2.2.6
Gradle

Librer�as externas:

Generador_Datos_Desafio_Tres-1.0.0.jar - Librer�a proporcionada por ustedes.
gson-2.8.2.jar - Esta librer�a fue necesaria incluirla para compilar el fuente proporcionado por ustedes.

Tambi�n se utilizaron librer�as contenidas en la versi�n Java 1.8
 
3.- Detalle de la compilaci�n y ejecuci�n
 
Tanto la compilaci�n como la ejecuci�n se realizaron por medio de Eclipse.
Se ejecuta la aplicaci�n como una Spring Boot App