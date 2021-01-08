# Laboratorio 1 - Grupo 18 - Equipo 2

Javier Sanz Fayos
Francisco José Cobo Celdrán
Alicia Amores Sánchez
Fernando Palomino Cobo
Monica Hazeu Gonzalez

### Para el laboratorio 1 de la asignatura de Percepción Computacional, se ha desarrollado una función que permite eliminar el artefacto de "ojos rojos" de una fotografía. 

La corrección se realiza detectando los ojos de la persona en la foto. Una vez detectados, se compara el valor de cada pixel de la zona "ojos" del canal rojo con la media de los valores de los canales azul y verde. Si este ratio es mayor que un umbral, se reduce el valor de intensidad del canal rojo.

En el caso de que se quiera aplicar la función a una imagen de un animal cuyos ojos no se parecen a los humanos (p.ej. un gato), se puede probar a utilizar una función alternativa que corregirá el canal rojo de toda la imagen, aunque con la consecuente reducción de tonos rojos de toda la imagen.

Librerías necesarias:

numpy, cv2, dlib, site, matplotlib.pyplot, os.path
