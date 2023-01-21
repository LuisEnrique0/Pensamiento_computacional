    Algoritmo Recomendacion
      op=0
      Escribir "Bienvenido a las recomendaciones de la ciudad. Selecciona una opción"

      Escribir " ~~~~~~~~~OPCIONES~~~~~~~~~~~~"
      Escribir "1.CINE"
      Escribir "2.LIBROS"
      Escribir "3.COMIDA"
      Escribir "4.LUGAR"
      Escribir "5.Salir"
      Leer op
      Mientras op <> 5 Hacer
        Segun op Hacer
          1:
            Escribir "Recomendaciones de CINE"
            Escribir "Aftersun. Disponible en Cineteca Nacional"
            Escribir "Avatar. Disponible en Cinepolis" 
          2:
            Escribir "Recomendaciones de LIBROS"
            Escribir "Pedro Paramo. Autor: Juan Rulfo"
            Escribir "Aura. Autor: Carlos Fuentes"
          3:
            Escribir "Recomendaciones de COMIDA"
            Escribir "Tacos al pastor"
            Escribir "Pozole"
          4:
            Escribir "Recomendaciones de LUGAR"
            Escribir "Zocalo"
            Escribir "Palacio de Bellas Artes"
          De Otro Modo:
            Escribir "Opcion invalida"

        Fin Segun
        Escribir " ~~~~~~~~~OPCIONES~~~~~~~~~~~~"
        Escribir "1.CINE"
        Escribir "2.LIBROS"
        Escribir "3.COMIDA"
        Escribir "4.LUGAR"
        Escribir "5.Salir"
        Leer op
    Fin Mientras
    Escribir "Gracias por utilizar recomendaciones"
    FinAlgoritmo
