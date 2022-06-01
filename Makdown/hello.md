 
<center> 
 
#  **Antipatrones De Diseño** 

</center>


## *¿Que es?*
<!--## *¿Como se compone?*-->
## *¿Tipos y definiciones?*  


<!--Comentario x-->

<br>
<br>

**Índice**   
1. [Primer apartado](#id1)
2. [Segundo apartado](#id2)


### *¿Que es un antipatron de diseño?*. <a name="id1"></a>

    Un antipatrón de diseño es un patrón de diseño que nos va a conducir a una mala solución a un problema.

    Es fundamental conocer los antipatrones de diseño, porque se considera una parte importante de una buena 
    práctica de programación.
    
    Como programador se deberían conocer los antipatrones para evitarlos siempre que sea posible, lo que requiere tener
    una cierta idea de los mismos para poder   reconocerlos, identificarlos y tan pronto como sea 
    posible eliminarlos dentro del ciclo de vida del desarrollo del software.
    
 #### *¿Que es un singleton?*<a name="id2"></a>


    Consiste en restringir la creación de objetos pertenecientes a una clase o el valor de un tipo a un único objeto,
    con la intención de garantizar que una clase sólo tenga una instancia y proporcionar un único punto de acceso global a ella.


Estos son solo algunos de los antipatrones que nos van a llevar a implementar malas soluciones.

Es bueno conocerlos también al igual que los patrones, ya que en este conocerlos va a permitir poder detectar a tiempo futuros problemas que van a desembocar en problemas mayores.


# *¿Como se compone o sus partes?*

Al utilizar antipatrones de diseño sabemos que como mala practica es necesaario identificarlos y conocer de ellos para asi evitarlos siempre que sea posible para asi eliminarlo del ciclo de vida del sofware y no obstruir su desempeño.

- Antipatrones de diseño de software, como podría ser generar una clase muy gorda, dotarla de demasiados atributos, 
    demasiados métodos y haciéndola responsable de, por ejemplo, prácticamente toda la lógica del negocio de la aplicación que 
    esté llevando.

    - Antipatrones de diseño Orientado a Objetos, como podría ser la Singletonitis, que es el abuso del patrón de diseño Singleton, 
    y que se considera una mala práctica.

    - Antipatrones de programación, cómo podría ser el conocido código espagueti, que consiste en construir sistemas sin estructuras 
    y difícilmente comprensibles.

    - Antipatrones metodológicos, como por ejemplo hacer programación de copiar pegar trozos de código en lugar de intentar hacer 
    soluciones genéricas.




 # *Tipos de antipatrones*.   

    Podemos encontrarnos con diferentes tipos de antipatrones:
###   Anti-patrones de Codificación

-Lava Flow:  como “programar al estilo volcán”. Es construir grandes cantidades de código de manera desordenada, con poca documentación y poca claridad de su función en el sistema, su característica principal es que entre mas crece el código mas difícil es su mantenimiento

-The God.- Un programa omnipresente y desconocido. Aquel sistema donde una sola clase ó modulo (la función main o equivalente) hace todo.

-Golden Hammer.- También conocida como la técnica de la barita mágica, es aferrarse a un paradigma intentar dar solución a un problema con el mismo leguaje de programación. 

-Spaghetti Code: código mal estructurado, con mala documentación donde el crecimiento en orden de la aplicación es nulo

-Fantasmas.- Demasiadas clases en un programa o tablas en una base de datos. Varias clases o tablas con mínimas responsabilidades. Muchas veces se utiliza para disfrazar la presencia del anti-patrón The God. Se colocan clases inútiles, que disfrazan el hecho que todo el sistema se encuentra construido en uno, o unos cuantos archivos, módulos o clases. +

### Anti-patrones de Arquitectura

-Reinventar la rueda.- Se refiere a Re implementar componentes que se pueden conseguir prefabricados de antemano, y hacer poco reusó en el código. En breves palabras: querer hacer todo uno mismo. 

Lo anterior, por lo regular, a causa de poco conocimiento del trabajo ya existente por parte del arquitecto, lo que conlleva a buscar soluciones para problemas ya solucionados.

-Casarse con el diablo.- Crear una dependencia hacia un fabricante que nos provee de alguna solución (componentes). El problema es inminente: 1. Se depende completamente de lo que el vendedor haga. 2. La calidad de los productos del proveedor nos comprometen. 3. El vendedor nos tiene agarrados. Cito como ejemplo, el caso de una de las universidades más importantes del país, cuyo desarrollo casi completo del sistema de administración escolar, está realizado sobre PL/SQL en Oracle.


### Anti-patrones de Administración de Proyecto

-The Mythical Month Man.- Mejor conocido como en el entorno como el “súper equipo de programadores”. Consiste en la creencia de que asignar más personal a un proyecto, acotará el tiempo de entrega. 

-Project Miss-management.- La jefa o el jefe que no saben coordinar. El proyecto se descuida y no se monitorea de manera adecuada, es muy difícil de detectar en etapas iniciales, pero repentinamente emerge de golpe y suele voltear de cabeza la situación del proyecto. Se manifiesta con retrasos en las fechas de entrega y/o áreas incompletas.




