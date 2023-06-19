# Python-Listas
Que son las listas en python, como crearlas, como modificarla, como eliminarlas y que beneficios nos traeria aprender

# Que son las listas en Python?

  Las listas son una estructura de datos, que se utiliza para contener o agrupar valores, las listas pueden contener objetos de cualquier tipo, numeros, cadenas de textos, booleanos e incluso otras listas. La forma de escrituracion de una lista es la siguiente:

      lista = [] # Lo que define a las liastas son los corchetes, por lo tanto el solo hecho de colocar corchetes ya estamos definiendo una         lista

  Como se puede observar, aqui tenemos una variable al cual le hemos asignado un corchete vacio, lo que significa que es una lista segun lo que hemos dicho anteriormente, por mas que esta este vacia, siempre y cuando mas adelante no se le asigne otro valor esto es una lista.

      print(type(lista)) # <class 'list'>

Otra de las cosas fundamentales que definen a una lista es que los items o datos que contienen estan separados por comas ' , '

      # Esta lista esta conformada por string o cadena de texto, por mas que sean numeros estos estan definidos como string
      lista = ['1','2','3','4','5']  

      # Esta lista esta conformada por numeros enteros y cadena de texto
      lista = [1,'2',3,'4','cinco','seis']

      # Esta otra lista, contiene numero enteros, string, decimales, booleano, otra lista, una coleccion de datos y un diccionario
      lista = [1, 'Hola', 3.14, True, [1, 2, 3], ('a', 'b', 'c'), {'nombre': 'Juan', 'edad': 25}]

      
