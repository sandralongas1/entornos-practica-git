[![Udemy](https://img.shields.io/badge/Udemy-A435F0?style=for-the-badge&logo=Udemy&logoColor=white)](https://www.udemy.com/)
[![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/)
# Lo aprendido en Markdown
> lo que encontraras a partir de ahora sera un indice de todo lo aplicado en este repositorio markdown.

## Índice
1. ***Elementos de bloque***
    - Párrafos y saltos de línea
    - Encabezados
    - Citas
    - _Listas_
    - Códigos de bloque
2. ***Elementos de línea***
    - Links o enlaces
    - Código
    - Imágenes

## Elementos de bloque
### Párrafos y saltos de línea 
Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una línea en blanco (pulsando dos veces intro).  __(↵) (↵)__

Para realizar un salto de línea y empezar una frase en una línea siguiente dentro del mismo párrafo, tendrás que pulsar dos veces la barra espaciadora **(--) (--)** antes de pulsar una vez intro (↵).  

Por ejemplo si quisieses escribir un poema quedaría tal que así:
            
        «Andando con sus patitas mojadas, (--) (--)  
        el gorrión (--) (--)    
        por la terraza de madera»

Donde cada verso tiene dos espacios en blanco al final.

### Encabezados
Las almohadillas son uno de los métodos utilizados en Markdown para crear encabezados. Debes usarlos añadiendo uno por cada nivel.  

        # Encabezado 1
        ## Encabezado 2
        ### Encabezado 3
        #### Encabezado 4
        ##### Encabezado 5
        ###### Encabezado 6

### Citas
Las citas se generar utilizando el carácter mayor que *>* al comienzo del bloque de texto.  
Si la cita en cuestión se compone de varios párrafos, deberás añadir el mismo símbolo > al comienzo de cada uno de ellos.  

        > Esto sería una cita como la que acabas de ver.
        > 
        > > Dentro de ella puedes anidar otra cita.
        > 
        > La cita principal llegaría hasta aquí. 

### Listas

A diferencia de lo que ocurre en HTML, generar listas en Markdown es tremendamente sencillo. Puedes encontrarte con dos tipos.
| Listas desordenadas  | listas ordenadas |
| ------------- | ------------- |
| *, - o +| numeros,  *, - o + |
|  Para crear listas anidadas dentro de otras, simplemente tendrás que añadir cuatro espacios en blanco  (--) (--) (--) (--)  antes del siguiente *, - o +.  |   Al igual que ocurre con las listas desordenadas, también podrás anidarlas o combinarlas. |

Para crear listas anidadas dentro de otras, simplemente tendrás que añadir cuatro espacios en blanco  (--) (--) (--) (--)  antes del siguiente *, - o +.

        - Elemento de lista 1
        - Elemento de lista 2
            - Elemento de lista 3
            - Elemento de lista 4
                - Elemento de lista 5
                - Elemento de lista 6
        Elemento de lista 1
        Elemento de lista 2
        Elemento de lista 3
        Elemento de lista 4
        Elemento de lista 5
        Elemento de lista 6
        Listas ordenadas
Para crear listas ordenadas debes utilizar la sintaxis de tipo: «número.» 1.. Al igual que ocurre con las listas desordenadas, también podrás anidarlas o combinarlas.

        1. Elemento de lista 1
        2.  Elemento de lista 2
            - Elemento de lista 3
            - Elemento de lista 4
                1. Elemento de lista 5
                2. Elemento de lista 6
        Elemento de lista 1
        Elemento de lista 2
        Elemento de lista 3
        Elemento de lista 4
        Elemento de lista 5
        Elemento de lista 6

### Códigos de bloque
Para crear un bloque entero que contenga código. Lo único que tienes que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ~ virgulillas.

Tal que así:  
            
        ~~~
        Creando códigos de bloque.
        Puedes añadir tantas líneas y párrafos como quieras.  
        ~~~
        De esta forma, obtendrás el siguiente resultado:
        
        Creando códigos de bloque.
        Puedes añadir tantas líneas y párrafos como quieras.

## Elementos de línea  
### Links o enlaces como referencia
Links o enlaces como referencia
La desventaja del método anterior, es que si utilizas links demasiado complejos o largos pueden dificultarte la lectura de tu texto.

Para solucionarlo y crear tu contenido de una manera más ordenada puedes generar enlaces de referencia.

Esto quiere decir que en tu texto enlazarás palabras o códigos concretos (formados por letras y/o números), que en otro lugar más apartado de tu documento tendrás definidos como determinadas URL.

        [Referencia para plantas][plantas]  
        [plantas]: https://viveiroscultiflor.pt/es/
Esto se ve más claro con un ejemplo.  

Me llamo Sandra y tengo un blog sobre [produccion de plantas][plantas].  
En dicha ***[web]***[plantas] recopilo artículos sobre todo lo relacionado con automatización, gestión y eficiencia.  

La referencia [plantas] puede estar incluida en cualquier parte del documento, así puedes organizarte mejor y de una manera más limpia, recopilando todas tus referencias en un mismo lugar.

[plantas]: https://viveiroscultiflor.pt/es/
        
### Código
Para mostrar código de otro lenguaje, atajos de teclado.

Para ello tienes disponible dos alternativas.

1).Código puro  &lt;code&gt;  
Envolver el texto entre dos comillas sencillas `. Esto se corresponde con la etiqueta HTML  &lt;code&gt;  

`Esto es una línea de código`


2).Texto preformateado &lt;pre&gt; 
La otra manera es comenzar el párrafo con cuatro espacios en blanco. Esto se corresponde con la etiqueta HTML  &lt;pre&gt;  
        
    Esto es una línea de código

### Imágenes
Insertar una imagen con Markdown se realiza de una manera prácticamente idéntica a insertar links.
Deberás añadir un símbolo de ! exclamación al principio y el enlace no será otro que la ubicación de la imagen.  

        ![Texto alternativo](/ruta/a/la/imagen.jpg "Título alternativo")
El texto alternativo es lo que se mostraría si la carga de la imagen fallase.
También podrás añadir un título alternativo entrecomillándolo al final de la ruta. Esto sería el título mostrado al dejar el cursor del ratón sobre la imagen.  

        ![nombre de la imagen](img1)
        ![ojo](https://github.com/sandralongas1/entornos-practica-git/blob/main/imagenes/proyecto1.jpg)
        

![](https://github.com/sandralongas1/entornos-practica-git/blob/main/imagenes/proyecto1.jpg "Arte moderno")  
