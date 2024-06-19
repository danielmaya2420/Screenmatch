El proyecto ScreenMatch es una aplicación que permite a los usuarios buscar y obtener información sobre películas. La aplicación utiliza la API de OMDB (Open Movie Database) para obtener los datos de las películas.
La API de OMDB es un servicio web que proporciona información sobre películas, series de televisión y otros contenidos audiovisuales. Permite realizar consultas y obtener datos como el título, el año de lanzamiento, la duración, el director, los actores, la trama, la calificación, entre otros.
En el proyecto ScreenMatch, se aplican los siguientes conceptos:

-Consumo de API: La aplicación utiliza la biblioteca Gson para realizar las solicitudes HTTP a la API de OMDB y procesar los datos JSON devueltos.

-Manejo de errores: El código utiliza bloques try-catch para manejar posibles excepciones que puedan ocurrir durante la comunicación con la API o al procesar los datos.

-Persistencia de datos: Los títulos de las películas buscadas se almacenan en un archivo JSON utilizando la clase FileWriter. Esto permite que los usuarios puedan acceder a la lista de películas consultadas anteriormente.

-Manipulación de listas: Se utiliza la clase ArrayList para almacenar y manejar la lista de títulos de películas.

-Modificación de objetos: Se realiza un override del método toString() de la clase Titulo para mejorar la presentación de los datos de las películas.

-Separación de responsabilidades: Se sugiere como un mini desafío separar el código en diferentes clases, como una clase encargada de obtener las películas de la API, otra clase para guardar los datos en el archivo JSON, y otra clase para transformar los datos de la API en objetos Titulo.

Estos conceptos son fundamentales en el desarrollo de aplicaciones Java y permiten crear soluciones más robustas, mantenibles y escalables.
