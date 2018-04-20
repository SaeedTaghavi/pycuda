Una introducción a CUDA y PyCUDA para científicos
===============

> “If debugging is the process of removing bugs, 
> then programming must be the process of putting them 
> in.” (Edsger W. Dijkstra)

Escritas por: Uriel Aceves y Leonardo Castro

Las notas que se encuentran en esta carpeta fueron escritas como parte de nuestro servicio social durante nuestra licenciatura en Física en la UNAM, con la intención de enseñar el lenguaje de programación CUDA C al lector, asi como el paradigma de la programación en paralelo. Puede tomarse como un curso introductorio a cursos de programación utilizando procesadores gráficos. El propósito principal de las notas es mostrar lo básico de CUDA y PyCUDA para que al completar la lectura y los ejercicios, el lector sea capaz de hacer sus propios programas en paralelo y tenga la posibilidad de acercarse a libros de enseñanza de CUDA tales como [CUDA by Example](https://developer.nvidia.com/content/cuda-example-introduction-general-purpose-gpu-programming-0) o [Programming Massively Parallel Processors](https://developer.nvidia.com/content/programming-massively-parallel-processors-hands-approach) y el lenguaje no sea tan árido como para una persona que nunca ha lidiado con C.

Las notas se dividen en dos partes principales:

##Parte I

| Capítulo              | Estado        |
---|:--
[Procesadores gráficos y CUDA](https://github.com/UriAceves/Servicio_social/blob/master/Parte%201%20-%20CUDA%20C/01%20-%20Procesadores%20graficos%2C%20CUDA%20y%20PyCUDA.ipynb) | Terminado
[Bases de CUDA](https://github.com/UriAceves/Servicio_social/blob/master/Parte%201%20-%20CUDA%20C/02%20-%20Bases%20de%20CUDA.ipynb) | Terminado
[Multiplicación de vectores](https://github.com/UriAceves/Servicio_social/blob/master/Parte%201%20-%20CUDA%20C/03%20-%20Multiplicacion%20de%20vectores.ipynb) | Terminado
[Patrones de comunicación](https://github.com/UriAceves/Servicio_social/blob/master/Parte%201%20-%20CUDA%20C/04%20-%20Patrones%20de%20comunicacion.ipynb) | Terminado
[Multiplicación de matrices](https://github.com/UriAceves/Servicio_social/blob/master/Parte%201%20-%20CUDA%20C/05%20-%20Multiplicacion%20de%20matrices.ipynb) | Terminado
[Programación con teselas](https://github.com/UriAceves/Servicio_social/blob/master/Parte%201%20-%20CUDA%20C/06%20-%20Programacion%20con%20tecelas.ipynb) | Terminado
[Ejercicios](https://github.com/UriAceves/Servicio_social/blob/master/Parte%201%20-%20CUDA%20C/07%20-%20Ejercicios.ipynb) | Terminado

##Parte II

| Capítulo              | Estado        |
---|:--
[Introducción a PyCUDA](https://github.com/UriAceves/Servicio_social/blob/master/Parte%202%20-%20PyCUDA%20y%20aplicaciones/01%20-%20Introduccion%20a%20PyCUDA.ipynb) | Terminado
[Distribuciones de probabilidad](https://github.com/UriAceves/Servicio_social/blob/master/Parte%202%20-%20PyCUDA%20y%20aplicaciones/02%20-%20Distribuciones%20de%20probabilidad.ipynb) | Terminado
[Caminantes aleatorios](https://github.com/UriAceves/Servicio_social/blob/master/Parte%202%20-%20PyCUDA%20y%20aplicaciones/03%20-%20Caminantes%20aleatorios.ipynb) | Terminado
[Ecuación maestra](https://github.com/UriAceves/Servicio_social/blob/master/Parte%202%20-%20PyCUDA%20y%20aplicaciones/04%20-%20Ecuacion%20maestra.ipynb) | Terminado
[Cadenas de Markov](https://github.com/UriAceves/Servicio_social/blob/master/Parte%202%20-%20PyCUDA%20y%20aplicaciones/05%20-%20Cadenas%20de%20Markov.ipynb) | Terminado
[Impresiones y tiempos](https://github.com/UriAceves/Servicio_social/blob/master/Parte%202%20-%20PyCUDA%20y%20aplicaciones/06%20-%20Impresiones%20y%20tiempos%20en%20PyCUDA.ipynb) | Terminado
[Operaciones con matrices](https://github.com/UriAceves/Servicio_social/blob/master/Parte%202%20-%20PyCUDA%20y%20aplicaciones/07%20-%20Operaciones%20con%20matrices.ipynb) | Terminado

##Apéndices

| Capítulo              | Estado        |
---|:--
[Instalación de CUDA C](https://github.com/UriAceves/Servicio_social/blob/master/Ap%C3%A9ndices/01%20-%20Instalacion%20CUDA%20Ubuntu.ipynb) | Terminado
[Instalación de git, julia y el ipython notebook](https://github.com/UriAceves/Servicio_social/blob/master/Ap%C3%A9ndices/02%20-%20Git%20basico.ipynb) | Terminado
[Números aleatorios con CUDA C](https://github.com/UriAceves/Servicio_social/blob/master/Ap%C3%A9ndices/03%20-%20cuRAND%20con%20CUDA%20C.ipynb) | Terminado

===

Se pueden encontrar otras notas de PyCUDA hechas por *Roberto Antonio Zamora Zamora* con un enfoque diferente [aquí](https://github.com/zamorays/miniCursoPycuda), se les sugiere a los lectores interesados en aprender más del tema, se acerquen a este sitio.

===

Una aclaración pertinente es el hecho de que no somos expertos en el tema de programación en paralelo, o el uso de CUDA y/o PyCUDA
sino que estas notas son el resultado de nuestro progreso desde no saber nada de CUDA hasta el punto
en que nos encontramos actualmente. Las notas fueron escritas a la par que fuimos aprendiendo y al final se revisaron para pulir detalles.
Si se complementan con algunos métodos numéricos bien podrían tener valía para un curso semestral de 3 horas semanales.

Agradecemos a la [Facultad de Ciencias](http://www.fciencias.unam.mx/) de la [UNAM](https://www.unam.mx/) por la educación y
las oportunidades que nos brindaron. Al [Dr. David P. Sanders](http://sistemas.fciencias.unam.mx/~dsanders/) ([perfil de GitHub](https://github.com/dpsanders)), nuestro tutor por su paciencia, sus acertadas observaciones, y proveernos un lugar para trabajar durante el desarrollo del proyecto.

Esperamos que estas notas cumplan su propósito: ayudar en la enseñanza y formación de científicos de calidad, para México y
América Latina. Que realmente este servicio social sea lo que su nombre pregona.

===

Si existen sugerencias o se detectan algunas erratas en las notas, comunicarse a los correos:
- uri.fisico@ciencias.unam.mx
- leonardo_castro@ciencias.unam.mx
