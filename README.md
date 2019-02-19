# Prueba Ingeniería Backend

Nos da gusto que quieras aplicar a trabajar como ingeniero en Resuelve, si quieres saber un poco más sobre Resuelve Ingeniería y el equipo puedes ver [aquí](https://github.com/resuelve/nuestro-equipo).

## Cálculo de Bonos 

El sueldo del equipo de football se compone de dos partes **un sueldo fijo** y **un bono variable**, la suma de estas dos partes hace el salario completo de un jugador. Tenemos varios criterios para poder calcular el bono variable que se divide en dos partes iguales **alcance de meta individual** y **alcance de meta por equipo**, es decir, 50% de meta individual y 50% de meta por equipo.

### ¿Cómo se calculan los alcances de meta y bonos? 

Todo jugador dependiendo de su nivel (A, B, C) tiene un número de goles mínimos que hacer cada mes:

| Nivel |Goles/mes|
| ------------- |:-------------:| 
|A |5|
|B |10|
|C |15|
|Cuauh |20|



El alcance de meta individual es el porcentaje de goles realizados contra el mínimo, es decir, si un Jugador C hace 15 goles en un mes tiene 100% de la parte proporcional de su bono que corresponte al alcance individual de la meta, si hace más de 15 sigue teniendo el 100% por que el % esta topado, pero, si hace 13 puntos tendría el 86%.

El alcance de meta del equipo es el promedio del alcance de meta individual de todos los miembros.

Ya sabiendo los porcentajes de alcance de meta tanto individual como por equipo ya podemos saber qué cantidad del bono le corresponde a cada jugador. 

## La prueba

Aquí en Resuelve nos gusta resolver problemas, pero también resolverlos con estilo, tu reto es que nos ayudes a calcular el sueldo final de los jugadores usando la información de arriba y el set de datos del servicio de abajo. Puedes usar el lenguaje que más te guste para desarrollar la prueba.

Recuerda que son dos equipos, de los que tienes que sacar sus bonos.

Una vez terminado tu aplicación es necesario que la subas a Github y le notifiques a tu contacto en Resuelve para que la revisen y te agenden una llamada para darte retro sobre tu proceso de aplicación. 

Puntos que calificaremos:

- Calidad de código
- Documentación
- Pruebas
- Cómo nos entregas tu aplicación para que la podamos correr

No olvides lucirte y dar lo mejor de ti. Aunque esta sea una aplicación sencilla trátala como si fuera un proyecto que irá directo a producción, tanto en calidad como en despliegue.

## Recursos

### Estructura de entrada de los miembros del equipo

```
[  
   {  
      "nombre":"Juan Perez",
      "nivel":"C",
      "goles":10,
      "sueldo":50000,
      "bono":25000,
      "sueldo_completo":null,
      "equipo":"rojo"
   },
   {  
      "nombre":"EL Cuau",
      "nivel":"Cuau",
      "goles":30,
      "sueldo":100000,
      "bono":30000,
      "sueldo_completo":null,
      "equipo":"azul"
   },
   {  
      "nombre":"Cosme Fulanito",
      "nivel":"A",
      "goles":7,
      "sueldo":20000,
      "bono":10000,
      "sueldo_completo":null,
      "equipo":"azul"

   },
   {  
      "nombre":"El Rulo",
      "nivel":"B",
      "goles":9,
      "sueldo":30000,
      "bono":15000,
      "sueldo_completo":null,
      "equipo":"rojo"

   }
]
```

### Respuesta

En la respuesta solo es agregar en la llave sueldo_completo la cadena del monto correcto para cada jugador.

```
[
   {  
      "nombre":"El Rulo",
      "goles_minimos":10,
      "goles":9,
      "sueldo":30000,
      "bono":15000,
      "sueldo_completo": "10000000"
   }
]
```

## ¿Llegaste aquí por casualidad?

Si llegaste aquí por casualidad y ya tienes la prueba resuelta, manda tus resultados a ing@resuelve.io para revisarla y agendar una llamada.



