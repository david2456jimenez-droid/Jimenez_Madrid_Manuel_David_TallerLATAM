Actores involucrados: 



**Administrador del sistema:** Responsable de la configuración general del sistema y sus catálogos base



**Personal de operaciones:** Encargado del registro y seguimiento operativo de los vuelos



**Personal de Atención al cliente:** Encargado del registro y gestion de la información de los pasajeros



1.2  Requisitos funcionales

El sistema debe permitir:

1\.	Registrar información de vuelos (número, origen, destino, fecha y hora de salida y llegada).

2\.	Gestionar datos de aeronaves (matrícula, modelo, capacidad).

3\.	Registrar información de la tripulación asignada a cada vuelo.

4\.	Gestionar datos de pasajeros (nombre, documento de identidad, contacto).

5\.	Generar reportes diarios de vuelos realizados.

 







3\.  Preguntas orientadoras

Antes de construir el modelo, resuelva estas preguntas. Le ayudarán a definir correctamente las entidades, relaciones y cardinalidades del sistema.

•	¿Qué tabla resuelve la relación muchos-a-muchos entre vuelos y tripulantes?

**Respuesta**: Una tabla asociativa es la encargada de obtener las PK de las dos tablas para que se pueda hacer la relación correctamente.



•	¿La aeronave se relaciona con el vuelo o con la aerolínea en general?

**Respuesta**: Una aeronave se relaciona con los vuelos ya que estos solo necesita saber hacia donde serán dirigido.



•	¿Un pasajero puede repetirse en varios vuelos sin duplicar sus datos personales?

**Respuesta**: No



•	¿Qué forma normal aplicaría para evitar guardar el modelo de la aeronave junto a cada vuelo?

**Respuesta**: 2FN



•	¿Qué información identifica de manera única a cada vuelo, y qué información identifica de manera única a cada reserva de un pasajero?

**Respuesta**: El Id



