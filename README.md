# Python-Listas
Que son las listas en python y sus caracteristicas

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


`#` Caracteristicas de las listas

  Las listas en python tienen algunas de las caracteristicas especificas que lo hacen el mas versatil dentro de los tipos compuestos que agrupan valores, y estas son:

  1- Ordenadas: Los elementos que componene una lista, se agrupan de forma ordenadas y especificas, lo que facilita enormemente poder acceder a dichos elementos por su posicion, es decir, los elementos que estan integrados dentro de una lista estan indexados al igual que una cadena de texto puede ser accedido al elemento especifico mediante su posicion en la lista, lo que facilita enormemente poder trabajar con con estos.
  2- Tamano del mismo: Las listas al igual que las cadenas de texto tiene una longitud o tamano, pero la lista a diferencia de las cadenas de textos son mutables es decir, pueden ser modificadas, ampliando o reduciendo su longitud o tamano, lo que como dijimos anteriormente es bastante util para poder trabajar con el mismo.
  3- Indexacion: Como hemos dicho anteriormente los elementos de una lista, estan ordenados e indexados, esto en razon de que cada elemento de una lista, a parte de su valor se encuentra ubicado en una posicion dentro de la lista o indic, que es un indice? es un número entero que indica la posición de un elemento en una lista, por ejemplo:

      lista = [1,2,3,4,5,6,7]
      # En este caso vemos una lista con siete elementos (independientemente del tipo de datos), cada uno de estos elementos, necesariamente dentro de una lista ocupan un indice, es decir el primer elemetento aparte de su valor que podria ser (string, un entero, un decimal, un booleano, otra lista, etc) tiene un indice indepedientemente de su valor, en este caso su valor es un entero (1), y su indice (0), se preguntaran por que el elemento 1 se encuentra en la posicion 0, esto por que las listas se indexan desde el numero 0 en adelante, por lo tanto, el primer elemento 1, tendria un indice de 0, mientras que el segundo elemento 2, tendria el indice 1 y asi hasta llegar al elemento 7, que tendria un indice 6 dentro de la lista.
      # Sabido esto, que funcion cumplen los indices? Su funcion al igual que las cadenas de textos, es la dar la capacidad de acceder a dicho elemento por su indice, por consiguiente, si quisieramos acceder a un elemento de una lista necesariamente tendriamos que utilizar un corchete inmediatemente despues de la variable que contiene la lista, en este caso lista seguido inmediamente de [], quedaria de la siguiente manera lista[], dentro del corchete tendriamos que indicar el indice al cual necesaitamos acceder.
      elemento1 = lista[0]
      print(elemento1) # Resultado = 1
      elemento2 = lista[6]
      print(elemento2) # Resultado = 7


4- Segmentación (slicing):
    La segmentación se utiliza para obtener subconjuntos de elementos de una lista. Permite seleccionar un rango de elementos en función de sus índices. La sintaxis de la segmentación consiste en especificar el índice de inicio, el índice de fin (no inclusivo) y, opcionalmente, el paso (el incremento entre los índices).

La sintaxis general es [inicio:fin:paso], donde inicio es el índice del primer elemento incluido, fin es el índice del primer elemento excluido y paso indica cuántos elementos se saltan en cada paso. Si no se especifican los valores de inicio y fin, se considera que toman los valores predeterminados de principio a fin de la lista.

Algunos ejemplos de segmentación en listas son:

    mi_lista[1:4]: Retorna una nueva lista con los elementos desde el índice 1 hasta el índice 3 (no inclusivo).
    mi_lista[:3]: Retorna una nueva lista con los primeros tres elementos de mi_lista.
    mi_lista[2::2]: Retorna una nueva lista con los elementos desde el índice 2 hasta el final, tomando solo cada segundo elemento.

La segmentación es útil para extraer porciones específicas de una lista y realizar operaciones o análisis en subconjuntos de elementos de manera más conveniente.

5- Operaciones de concatenacion:
  Al igual que en las cadenas de textos pueden ser concatenadas, es decir unir dos o mas listas, veamos un ejemplo.

      lista1 = [1,2,3]
      lista2 = [4,5,6]

      lista3 = lista1 + lista2
      print(lista3) # Resultado [1,2,3,4,5,6]

  Esto es suficientemente utiliz, para agrupar listas en una sola lista mas grande y poder trabajar de una forma mas ordenada.

6- Metodos y funciones: Las listas vienen incorpordas con ciertos metodos para manipular las listas como asi tambien a traves de funciones se puede realizar ciertas operaciones especificas, como conocer el largo de una lista, este tema lo tocaremos en otra oportunidad.

7- Puede contener o no elementos duplicados: dentro de las listas a diferencia de otros tipos de conjuntos de datos, puede contener elementos repetidos, por ejemplo:

      lista = ['Luis','Luis','Perez', 1,3,4, 1,3,4]
      # Esto no acarrearia ningun tipo de error


Con esto hemos visto en este apartado lo suficiente para tener una idea clara de que son las listas y cuales su caracteristicas que lo hace el mas versatil dentro de los tipos de agrupadores de datos dentro de python.
