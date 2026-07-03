**3.  Preguntas orientadoras**



Antes de construir el modelo, resuelva estas preguntas. Le ayudarán a definir correctamente las entidades, relaciones y cardinalidades del sistema.



•	¿Qué tabla resuelve la relación muchos-a-muchos entre vuelos y tripulantes?

Respuesta: Se agregaría una tabla compuesta en la cual se agregaría la PK de las dos tablas las cuales pasan a ser FK en esta tabla y así solucionar el problema N:M



•	¿La aeronave se relaciona con el vuelo o con la aerolínea en general?

Respuesta: Con el vuelo ya que este mismo tiene todos los datos necesarios que necesita el piloto de la aeronave para orientarse hacia donde ira.



•	¿Un pasajero puede repetirse en varios vuelos sin duplicar sus datos personales?

Respuesta: Si, un pasajero puede comprar varias reservas y no necesariamente necesita repetir o duplicar sus datos personales ya que estos datos personales deberían guardarse en una tabla separada de los vuelos para evitar el duplicado de datos innecesarios.



•	¿Qué forma normal aplicaría para evitar guardar el modelo de la aeronave junto a cada vuelo?

Respuesta: Respuesta: La tercera forma normal ya que esta misma dice que un atributo no clave no puede depender de otro atributo no clave en este caso un modelo de aeronave pertenece únicamente a una matrícula en este caso el modelo depende de la matricula pero como la matricula es un atributo no clave entonces esta rompe la 3FN y se resolvería separando el modelo de vuelos



•	¿Qué información identifica de manera única a cada vuelo, y qué información identifica de manera única a cada reserva de un pasajero?

Respuesta: El dato único de cada vuelo seria la fecha y el dato único de la reserva es el ID.



