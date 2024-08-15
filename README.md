## Historia de usuario 1

1.i.¿Qué propósito cumple el archivo main.ts en un proyecto NestJS y por qué es crucial en la configuración inicial? Puedes leer más sobre el archivo aquí en la sección inferior de notas. <br><br>

R// Lo que hace main es que ahi es el punto de partida de nuestra app y es donde va toda la configuracion de nuestro proyecto para que escuche por el puerto y  tambien para es el archivo que conecta todos los componentes antes de que la aplicación comience a procesar solicitudes.<br><br>

1.ii.¿Qué diferencia existe entre app.module.ts y app.controller.ts? ¿Cómo se relacionan estos archivos con la modularidad y la estructura de la aplicación? Puedes leer sobre el archivo aquí o aquí.<br><br>

R// El app.module.ts es quien se encarga de agrupar todo lo que es los controller, service modulos que se encuentran el la aplicacion y es la que se encarga de ensamblar nuestra app y ya el controlador es quien tiene la capa de presentacion de nuestra aplicacion  y tambien en retonarle un respuesta a nuestro cliente <br><br>

2.i.¿Por qué crees que es importante modularizar la aplicación separando funcionalidades en diferentes módulos?<br><br>

R//Por que asi podemos separar responsabilidades mas facil y mas legible para otros coder que quiera leer nuestro codigo o a nosotros mismo para poder entender <br><br>

2.ii.¿Cómo crees que afecta la modularidad al mantenimiento y escalabilidad de la aplicación?<br><br>

R//es muy importante por que es mas facil escalar y saber que vas a modificar si hay separacion de responsabilidades 

2.iii.Despues de crear los archivos de los módulos, ¿qué archivos se generan y cómo se relacionan con los módulos creados?<br><br>

R//genera los app que seria controllers, service , module y esto se relacion ya que esta es la estructura basica que necesita nuestra app para funciona.<br><br>

3.i.¿Qué sucede si defines incorrectamente un decorador en un controlador? ¿Cómo afecta esto a la funcionalidad del endpoint?<br><br>

R//Si definimos mal un decorador lo que pasaria es que no funcionaria ya que esta mal definido y romperia nuestra app y al llamar este  enpoint se estallaria<br><br>

3.ii.¿Por qué es importante manejar rutas dinámicas (por ejemplo, @Get(':id')) en aplicaciones que interactúan con bases de datos?<br><br>

R//Por que es mucho mejor para poder hacer busquedas mas rapida y con menos recursos<br><br>

## Historia de usuario 2

1.i.¿Qué ventajas tiene manejar la lógica de negocio en servicios en lugar de controladores?<br><br>

R//al separar la logica de negocio e smas facil editar si queires cambiar algo y tienes menos probabilidades de cometer un error<br><br>

1.ii.¿Cómo se relaciona la inyección de dependencias con la modularidad y la capacidad de prueba de la aplicación?<br><br>

R// por que en el module se hace la inyeccion de dependecias y asi es mas facil probar pequeñas partes de la app<br><br>

2.i.¿Por qué es crucial validar los datos de entrada en una aplicación que maneja transacciones financieras?<br><br>

R// por que puede ser que el cliente no este cumpliendo el contarto y nos este injecto datos que no queremso y que pueden ser perjudiciales para nuestro negocio<br><br>

2.ii.¿Qué podría suceder si un decorador está mal colocado o si no se aplican los pipes correctamente?<br><br>


