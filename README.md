# Prueba Ingeniería Backend

Nos da gusto que quieras aplicar a trabajar como ingeniero en Resuelve, si quieres saber un poco más sobre Resuelve Ingeniería y el equipo puedes ver [aquí](https://github.com/resuelve/nuestro-equipo).

## Calculo de Bonos 

El sueldo del equipo de football se compone de dos partes **un sueldo fijo** y **un bono variable**, la suma de estas dos partes hace el saliario completo de un jugador. Tenemos varios criterios para poder calcular la parte variable que se divide en dos **alcance de meta individual** y **alcance de meta por equipo**.

### ¿Cómo se calculan los alcances de meta y bonos? 

Todo jugador dependiendo de su nivel (A, B, C) tiene un número de goles mínimos que hacer cada mes:

| Nivel |Goles/mes|
| ------------- |:-------------:| 
|A |5|
|B |10|
|C |15|

El alcance de meta individual es el porcentaje de goles realizados contra el mínimo, es decir, si un Jugador A hace 15 goles en un mes tiene 100% de la parte proporcional de su bono que corresponte al alcance individual de la meta, si hace más de 15 sigue teniendo el 100% por que el % esta topado, pero, si hace 13 puntos tendría el 86%.

El alcance de meta del equipo se calcula sacando un promedio del alcance de meta individual de cada miembro del equipo.

Ya sabiendo los porcentajes de alcance de meta tanto individual como por equipo ya podemos saber qué cantidad del bono le corresponde a cada jugador. 

## La prueba

Aquí en Resuelve nos gusta resolver problemas, pero también resolverlos con estilo, tu reto es que nos ayudes a calcular el sueldo final de los jugdores usando la inforamción de arriba y el set de datos del servicio de abajo. Puedes usar el lenguaje que más te guste para desarrollar la prueba.

Una vez terminado tu aplicación es necesario que la subas a Github y le notifiques a tu contacto en Resuelve para que la revisen y te agenden una llamada para darte retro sobre tu proceso de aplicación. 

Puntos que calificaremos:

- Calidad de código
- Documentación
- Cómo nos entregas tu aplicación para que la podamos correr

No olvides lucirte y dar lo mejor, que todo eso se toma en cuenta, aun que sea una aplicación sencilla puedes dockerizarla para que sea más fácil de ejecutar.

## Recursos

