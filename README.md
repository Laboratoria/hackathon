# Challenge Hackathon

¡Bienvenida a la hackathon de finalización del Bootcamp!. En esta ocasión, en preparación para el talent fest, cada squad tendrá asignado un reto. Puedes ver los retos al final de este documento.

Como en toda hackathon se valorará la buena utilización del tiempo (poder terminar un producto en un período corto de tiempo), la implementación de la solución y la sustentación de la misma.

Para esta hackathon tendrás 3 días en el salón de clases más las horas adicionales que puedas, junto con tu equipo, dedicarle fuera del salón.

## Reglas generales:

- El trabajo es en squads de 4-5 personas
- Todos los squads estarán conformados por especialidades mixtas: FED + UXD
- Duración: 3 turnos en la sala de clases y todo el tiempo adicional que quieran/puedan trabajar.
- Demos: habrá una al final de la hackathon mostrando el producto final
- Herramientas:
  - Utiliza github para organizar tu flujo de trabajo
  - Muestra el proceso de trabajo en el README.md
  - Usa React
  - Bonus: despliega tu producto en Heroku

## Demos

Las demos se realizarán el tercer día a partir de las 3:30 pm. A esa hora, se acondicionará la sala de clases para tener una “feria de demos”. Durante una hora los miembros del equipo de Laboratoria pasarán por los sitios de cada squad viendo las demos. Las demos no deben durar más de 3 minutos y deben mostrar el producto y los frameworks / soluciones que se utilizaron.
Para estas demos, el producto deberá estar desplegado en algún servidor (Github, Firebase, Heroku o AWS), no se permitirán demos desde localhost. 
Los miembros del equipo votarán por los 5 equipos finalistas, quienes tendrán la oportunidad de hacer su demo a todo el público para poder elegir un ganador. Estas presentaciones finales se realizarán a las 5 pm y deberán tomar 3 minutos c/u.

## Recomendaciones:

- Google y el contenido en el LMS son tus mejores amigos, úsalos.
- Empieza el día de trabajo con un daily y termínalo con una retrospectiva
- Utiliza todos los conocimientos/habilidades que has adquirido en tu tiempo en Laboratoria
- Trata todo el tiempo de tomar tiempo a todas las actividades (timeboxed).
- Organícense sobre cómo trabajarán en GIT.
- Prefiere siempre pocas cosas funcionando OK que muchas “a medias”.

## Agenda propuesta:

### Sesión 1:
- Presentación de la hackathon
- Planificación del trabajo
- Ideación del producto
- Trabajo en el producto

### Sesión 2:

- Trabajo en el producto

### Sesión 3:

- Trabajo en el producto
- Demos

## Retos

### Crear un styleguide de Laboratoria con componentes en React

Crea un styleguide de componentes para Laboratoria utilizando el nuevo branding. Puedes proponer nuevos elementos o
mejoras a los elementos existentes. En este [link](http://laboratoria.la/) puedes encontrar algunos componentes hechos
con el nuevo branding.  

La propuesta de styleguide es libre. Si quieres una referencia, [esta](https://polaris.shopify.com/components/get-started/ ) es la que más nos gusta.

### Crear un app de clima

Crea un app para chequear las condiciones de clima, puedes usar cualquier API de clima para ayudarte, que todos los días te muestre el clima del día y te pregunte como sientes el clima, por ejemplo frío, muy frío, caluroso, perfecto, etc. El app deberá guardar tus respuestas sobre el clima para luego relacionarlas con el pronóstico y decirte cómo te sentirás ese día. 

### Bikesantiago

El app de [Bikesantiago](https://play.google.com/store/apps/details?id=com.bikesantiagoapp) tiene solo 2.1 estrellas en el play store. Ayúdanos a entender por qué tiene tan bajo rating y cómo podemos hacer para mejorar la experiencia y el rating del app. 

* Si estás fuera de Santiago, piensa en un servicio similar para tu ciudad.

### Eventos

Vamos a crear una web app para organizar eventos considerando:
1. Existen al menos 2 sesiones simultáneas. Por ejemplo, dos speakers en dos lugares diferentes a la misma hora.
2. Hay cupos limitados para los asistentes
3. “Admin” crea eventos y cantidad de cupos para cada cual
4. Usuarios se pueden registrar en los eventos que quieran
  - No puede registrarse a la misma hora en más de un evento
  - Los cupos se van agotando
5. Bonus:
  - Chat general para cada sesión
  - Ping a asistentes para pedir contacto para networking. El que recibe el ping, acepta o no el pedido. TBD

### Integrarse con un backend

Tenemos un app construida en Ruby on Rails que utiliza una base de datos en Postgres. El app no está completa, por lo que es necesario trabajar en back-end y front-end para tener un app más completa. 
Tendrás que clonar este [reposotorio](https://github.com/Laboratoria/hackathon-rails). 

En la rama `master` del repositorio están las instrucciones de cómo instalar ruby, ruby on rails y postgres en tu computador, ya sea Windows o Ubuntu. Sigue las instrucciones y estarás lista. En la rama `main` está el proyecto sobre el cual tendrs que trabajar. 

El app en el que vas a trabajar es un catálogo de productos de una tienda. Donde existen 2 tipos de usuarios: el administrador del catálogo y los compradores. El administrador del catálogo tiene un acceso privado (login) a varios formularios donde puede agregar, editar, eliminar actualizar productos. Estos productos pertenecen a distintas categorías. Cada producto tiene sus propias descripciones, precios, stock e imagen. Por otro lado, los compradores podrán ver el catálogo de productos y entrar en el detalle de cada producto.

- Crear un seed de categorias y productos para que el app pueda tener una base de datos más grande y diversa
- Mantener Materialize como framework
- Trabajar en todas las vistas del app para que sean más amigables y puedan transmitir conexión con la marca a los usuarios
- Agregar validaciones en los formularios
- Agregar paginaciones cuando la lista de productos sea mayor a 10 (puedes hacerlo desde el back-end o desde el front-end)
- Agregar breadcrumbs (migas de pan) a las vistas.
- Sustituir o crear una vista de productos donde se pueda filtrar por categoría.
- Desplegar el app en Heroku

### Replicar el app de Square POS

Square POS es una de las mejores apps de punto de venta, sin embargo, no tiene aún soporte para latinoamérica.[Este](https://squareup.com/pos) es el app y [aquí](https://www.youtube.com/watch?v=D3uwIww7flw 
) puedes ver un video de sus principales funciones. La idea es que crees un app parecida pero adaptada a las necesidades de tu país en términos de flujos, monedas e impuestos.

¿Qué funcionalidades debes priorizar?

- Catálogo de productos con precios y stocks
- Cobros en efectivo y tarjeta de crédito (intenta usar un API)
- Cuadre de caja al final del día

### The bible app o aplicaciones similares

Elige un app, del app store o play store, que tenga muchas descargas pero que su experiencia no sea tan buena. Testéala, re-diséñala e impleméntala.
